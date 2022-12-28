# deliveryapp
HTTP requests: A delivery app will likely need to make HTTP requests to a server to retrieve data and to update data. In React, you can use the fetch API or a library like Axios to make HTTP requests.
Components: The DeliveryApp component is a self-contained piece of code that defines the layout and behavior of the delivery app.
State: The deliveries state variable is used to store the list of deliveries, and the setDeliveries function is used to update the state when a new delivery is added.
Props: The deliveries state variable is passed as a prop to the <ul> element, which uses it to render a list of deliveries.
Event handling: The handleAddDelivery function is used to handle the submit event of the form, which adds a new delivery to the list when the form is submitted.
the useEffect hook to make an HTTP GET request to the /api/deliveries endpoint when the component is mounted. The response from the server is then used to update the state with the list of deliveries.

The axios library is used to make the HTTP request, but you can also use the fetch API or another library like request to make HTTP requests in React.
