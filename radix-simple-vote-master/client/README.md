# Radix Simple Vote Frontend 

That is a first test try to use Radix with the goal to discover how to build.
I have been following and understaning how to create a voting system using the Radix tooltip.
I has been a good experiance to discover from Radix.


## Development

Install it and run:

```sh
npm install
npm start
```

Follow the setup instructions above, then:

- Open the url shown from `npm start` in the browser with the Radix extension
- Click the "Connect" button and keep the wallet open on your phone to respond to
  transaction signing requests
- The app will show different buttons based on the state of the vote on chain,
  starting with a button to instantiate a new vote component

Note:

- The vote blueprint is already deployed on RCNet and the package address is
  hard-coded into the app

## Deploy

Build the production site:

```sh
npm run build
```

Deploy a preview with:

```sh
npx netlify deploy
```

Deploy to prod with:

```sh
npx netlify deploy --prod
```

## References

I have learned and try to undersant from the work of rynoV voting solution. https://github.com/rynoV/radix-simple-vote
