Redux tookit basics implemented in a simple counter
1. create store.js (import configureStore,export store and also create a store using configureStore and then add a reducer in it)
2. Make sure to wrap the App component in inddex js inside a Provider to provide the store along all child components
3. create a Slice (import createSlice and then initialize the initialState and create the slice including a name,initialstate and reducers and create functions there)
4. use the hooks useSelector and useDispatch in the respective components to further use the state and actions