# Application Architecture, MVC Design Pattern
01. What are the Pillars of Object Oriented Programming (`OOP`)?
  
  > | Abstraction, Encapsulation, Inheritance, Polymorphism = APIE |

02. How does `export` differ from `export default`?
  
  > | When I want to export multiple, named objects, I would use export.  Export default is used for a single export under the default name. |

03. What is Encapsulation?
  
  > | From my reading: Encapsulation is the bundling of data and the methods that act on that data such that access to that data is restricted from outside the bundle, or as Alan Kay describes it, “local retention and protection and hiding of state-process.” In OOP, that means that an object stores its state privately, and only the object’s methods have access to change it. Isolate code between private and non-private - keeping the internal state hidden from prying eyes. |

04. What are some of the benefits of the `Proxy` object that we are using in our structure for applications?
  
  > | When I create a proxy, I override the get operator to prevent me from accessing the id property...I'm still re-reading and grappling with this concept, tbh - good for security,  |

05. What the difference between a `class` and an instance of a `class`?
  
  > | Static classes cannot be instantiated, whereas non-static classes can have both instance methods and static methods. class is the blueprint. |

06. What is a computed Property?
  
  > | Computed properties work similarly to methods, but only run when one of their dependencies changes. getters and setters |

07. What is the purpose of the `MVC` pattern?
  
  > | Organization of large projects that creates a standard for teams to understand and work within. controlling flow of information and providing encapsulation |

08. What is the job of the `Controller` in the `MVC` Pattern?
  
  > | The controller interacts with the HTML/User, receiving input and drawing to the page |

09. What is the job of the `Service` in `MVC`?
  
  > | Logistical operations are done in the Service. Manipulate the data within the appState. |

10. What is the job of the `Model` in `MVC`?
  
  > | The model stores and emits blueprints for the constructors to build with |
