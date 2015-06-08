## Oraganizing rules
When writing style rules for each of your selectors, you can suddenly get lost between so many declarations.

To mantain things easy to understand, a good way to write and organizing rules is to start describe styles *from generic aspects to specific* ones, *grouping them by type*.

The main advantage of doing this is you can easily *design* the element in your mind while you read the rules besides the fact you can always count on certain properties being in the same place (faster scan).

### Example
```
.selector {
  /* Positioning */
  display: inline-block;
  position: relative;

  /* Spacing and Size */
  margin: 10px 20px;
  padding: 5px;
  width: 100px;
  height: 100px;

  /* Color */
  background: #000;
  color: #fff
  
  /* Text */
  font-family: sans-serif;
  font-size: 16px;
  font-style: italic;
  line-height: 1.5;
  text-align: center;
  text-decoration: none;
  text-shadow: 2px 2px #ff0000;
  
  /* All the other not so common rules */
  -webkit-box-shadow: 10px 10px 5px 0px rgba(0,0,0,0.75);
  -moz-box-shadow: 10px 10px 5px 0px rgba(0,0,0,0.75);
  box-shadow: 10px 10px 5px 0px rgba(0,0,0,0.75);
  cursor: pointer;
  box-sizing: border-box;
  z-index: 10;
}
```
