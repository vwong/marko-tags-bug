This repo demonstrates a bug with the latest Marko Tags API Preview.

Run `npm run dev` and visit http://localhost:3000

Then, open the flyout, and try to click the action button nested within.  Notice that nothing happens.

Uncomment the state variable inside `<action-in-flyout>`, and it works again!
