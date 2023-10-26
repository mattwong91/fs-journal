# Single Page Applications with Vue
01. What is the entrypoint of an application?

  > | The point where a program begins. In our case its the main.js file |

02. What is the difference between a vue `component` and `page`?

  > | A page is parent level component that is responsible for the main content of a given page. They have unique URLs and aren't reused in other places within the application. A component is a piece of html or template that can be reused in multiple locations within a program or application |

03. What is ***Component-Based Architecture***?

  > | It's a structure that uses smaller interfaces or 'components' which are able to be repeated or reused in multiple places within an application. These components are encapsulated and act independently from each other. |

04. What are the three tags that make up a Vue component?

  > | Template, Script, Style |

05. What are ***lifecycle hooks***? What are lifecycle hooks used for?

  > | Lifecycle hooks are points within the time that a compenent exists that are accessible to the programmer. You can insert code into these different points of the creation, mounting, destruction, etc. to perform tasks that may be required before another hook is run. |

06. Which component in Vue does the vue-router use to mount pages onto?

  > | The vue-router uses the App component to mount pages into the router-view |

07. What is the difference between the `AppState` and the state object within a component?

  > | The state object in a component describes the local state of the component. The AppState is an abstracted global place to store the state of the full application. |

08. What is the responsibility of `Services` in our Vue projects?

  > | Services are responsible for manipulating data within our AppState and making calls to APIs |

09. What are ***props*** and how are they used? Provide an example

  > | Props are essentially parameters that get passed from a parent component to a child component. That data can then be accessed within the child component. One example would be passing down an object we've iterated in the parent component using a v-for and then being able to template our html in the child component using the prop that was passed. (ex: Passing car allows the child to use car.make, car.model in it's template) |

10. What is the Vue method used to create watchable objects such as `state` or `AppState`?

  > | It's the `reactive()` method. |
