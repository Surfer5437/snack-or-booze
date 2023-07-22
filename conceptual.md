### Conceptual Exercise

Answer the following questions below:

- What is the purpose of the React Router?
  the purpose of the react router is to simplify switching to different page components.
- What is a single page application?
  a single page that never sends a new request to switch between different pages.
- What are some differences between client side and server side routing?
  server side routing means that the server is responsible for getting and sending diffent page
  data based on the URL vs client side routing leaves the browser on the clients device responsible for displaying page content.
- What are two ways of handling redirects with React Router? When would you use each?
  having the <redirect> to send a user to a 404 page if the page isnt found and the .push method that is used for
  sending the user somewhere after they have completed a form(for example).
- What are two different ways to handle page-not-found user experiences using React Router?
  have an empty route that matches when all other routes fail to match or an <redirect to='/not_found'> component.
- How do you grab URL parameters from within a component using React Router?
  using the useParams method with a named parameter in the URL.
- What is context in React? When would you use it?
  using context helps so that you dont have to pass parameters from parent, to child, to grandchild, etc.
- Describe some differences between class-based components and function
  components in React.
  class-based components are more used for an app-wide functionality to prevent duplicating the same code but the
  function components are more based on each component and used in that specific component or passed down as a prop to a child.
- What are some of the problems that hooks were designed to solve?
  hooks were designed to make react more friendly to new developers and to help reduce some of the leg work in developing applications.
