# React
  React is a JavaScript library for building use interfaces.<br>
  *  **Declarative:**React makes it painless to create interactive UIs. Design simple views for each state in your application, and React will efficiently update and render just the right components when your data changes. Declarative views make your code more predictable, simpler to understand, and easier to debug.
  * **Component-Based:** Build encapsulated components that manage their own state, then compose them to make complex UIs. Since component logic is written in JavaScript instead of templates, you can easily pass rich data through your app and keep state out of the DOM.
  * **Learn Once, Write Anywhere:** We don't make assumptions about the rest of your technology stack, so you can develop new features in React without rewriting existing code. React can also render on the server using Node and power mobile apps using[React Native.](https://reactnative.dev/)<br>
  [Learn how to use React in your own project.](https://reactjs.org/docs/getting-started.html)
  # Installation
  React has been designed for gradual adoption from the start, **and you can use as little or as much React as you need:**
  * Use [ Online Playgrounds](https://reactjs.org/docs/getting-started.html#online-playgrounds) to get a taste of React.
  * [Add React to a Website
](https://reactjs.org/docs/add-react-to-a-website.html)as a `<script>` tag in one minute.

  * [Create a New React App](https://reactjs.org/docs/create-a-new-react-app.html)if you're looking for a powerful JavaScript toolchain.
  You can use React as a`<script>`ag from a [CDN](https://reactjs.org/docs/cdn-links.html) or as a `react` package on [npm.](https://www.npmjs.com/package/reactl)
  # Documentation
  You can find the React documentation [on the website.](https://reactjs.org/)
  Check out the [Getting Started](https://reactjs.org/docs/getting-started.html) page for a quick overview.  <br>   The documentation is divided into several sections: <br>
  * [Tutorial ](https://reactjs.org/tutorial/tutorial.html)
  * [Main Concepts ](https://reactjs.org/docs/hello-world.html)
  * [Advanced Guides ](https://reactjs.org/docs/jsx-in-depth.html)
  * [API Reference ](https://reactjs.org/docs/react-api.html)
  * [Where to Get Support ](https://reactjs.org/community/support.html)
  * [Contributing Guide](https://reactjs.org/docs/how-to-contribute.html)<br>
  You can improve it by sending pull requests to [this repository.](https://github.com/reactjs/reactjs.org)
  # Examples
  We have several examples [on the website.](https://reactjs.org/) Here is the first one to get you started:
  > function HelloMessage({ name }) {                           <br>
      return `<div>`Hello {name}`</div>`;                       <br>
}                                                               <br>
ReactDOM.render(                                                <br>
  `<HelloMessage name="Taylor" />`,                             <br>
  document.getElementById('container')                          <br>
);                                                              <br>

  This example will render "Hello Taylor" into a container on the page.
  You'll notice that we used an HTML-like syntax; [we call it JSX.](https://reactjs.org/docs/introducing-jsx.html) JSX is not required to use React, but it makes code more readable, and writing it feels like writing HTML. If you're using React as a`<script>`tag, read [this section](https://reactjs.org/docs/add-react-to-a-website.html#optional-try-react-with-jsx) on integrating JSX; otherwise, the [recommended JavaScript toolchains](https://reactjs.org/docs/create-a-new-react-app.html) handle it automatically.

  # Contributing

  The main purpose of this repository is to continue evolving React core, making it faster and easier to use. Development of React happens in the open on GitHub, and we are grateful to the community for contributing bugfixes and improvements. Read below to learn how you can take part in improving React.

  ## [Code of Conduct](https://code.fb.com/codeofconduct)

  Facebook has adopted a Code of Conduct that we expect project participants to adhere to. Please read [ the full text](https://opensource.fb.com/code-of-conduct/) so that you can understand what actions will and will not be tolerated.

  ## [Contributing Guide](https://reactjs.org/docs/how-to-contribute.html)

  Read our [contributing guide](https://reactjs.org/docs/how-to-contribute.html) to learn about our development process, how to propose bugfixes and improvements, and how to build and test your changes to React.

  ## Good First Issues
  To help you get your feet wet and get you familiar with our contribution process, we have a list of [good first issues](https://github.com/facebook/react/labels/good%20first%20issue) that contain bugs which have a relatively limited scope. This is a great place to get started.

  ## License

  React is [MIT licensed.](https://github.com/facebook/react/blob/main/LICENSE)