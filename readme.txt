Lazily initialize our `notes` state so it doesn't
     * reach into localStorage on every single re-render
     * of the App component

* Lazy state initialization: Any expensive code running inside
	*our state initialization
	*should happen only one time

* Lazy state initialization:
	*instead of directly initializing the state with a value
	*initialize the state with a function that returns a value

npm install --save nanoid
npm install --save react-split
npm install --save react-showdown
npm i --f react-mde