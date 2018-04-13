# LearningReact8
Chapter 10 - Working with Events and

Now, here is something I learned the hard way. Don't refer to traditional DOM event documentation when using Synthetic events and their properties. Because the SyntheticEvent wraps your native DOM event, events and their properties may not map one-to-one. Some DOM events don't even exist in React. To avoid running into any issues, if you want to know the name of a SyntheticEvent or any of its properties, refer to the React Event System document(https://facebook.github.io/react/docs/events.html)	instead.
