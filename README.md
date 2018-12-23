# react-snippets README

## Note

React code snippets is still under development and will change regularly! Any
contributions or remarks are welcome as we progress to a fixed version.

## Supported languages

- Javascript
- Javascript React

## Snippets

### Components

|      How | What                                             | Alternative keys                            |
| -------: | ------------------------------------------------ | ------------------------------------------- |
|   `memo` | Stateless react memo component                   | -                                           |
|  `memop` | Stateless react memo component with proptypes    | `memo`                                      |
|    `rsc` | Stateless react component                        | `comp`                                      |
|   `rscp` | Stateless react component                        | `comp`, `rsc`                               |
|   `pure` | Pure component react                             | -                                           |
|  `purep` | Pure component react with proptypes              | `pure`                                      |
|  `compo` | Regular react component                          | `comp`                                      |
|  `compp` | Regular react component with proptypes           | `comp`                                      |
|  `rcomp` | Regular react component with redux               | `comp`, `rrc`, `reduxcomp`                  |
| `rcompp` | Regular react component with redux and proptypes | `comp`, `rcomp`, `rrc`, `rrcp`, `reduxcomp` |

### Functions

|        How | What                                   | Alternative keys                                   |
| ---------: | -------------------------------------- | -------------------------------------------------- |
|     `bind` | React bind functions to 'this' context | -                                                  |
| `setstate` | React set state function               | `sets`, `ss`                                       |
|     `defp` | React Proptypes definition             | `def`, `defprops`, `dp`, `default`, `defaultprops` |
|     `prop` | React Proptypes definition             | `proptypes`, `pt`                                  |
|      `ren` | React render function                  | `render`                                           |

### PropTypes

|          How | What                               | Alternative keys                                          |
| -----------: | ---------------------------------- | --------------------------------------------------------- |
|     `number` | React PropType Number              | `prop`, `propn`, `propnumber`                             |
|     `number` | React PropType Number Required     | `prop`, `propn`, `propnumber`, `propr`                    |
|     `string` | React PropType String              | `prop`, `props`, `propstring`                             |
|     `string` | React PropType String Required     | `prop`, `props`, `propstring`, `propr`                    |
|      `array` | React PropType Array               | `prop`, `propa`, `proparray`                              |
|      `array` | React PropType Array Required      | `prop`, `propa`, `proparray`, `propr`                     |
|       `bool` | React PropType Bool                | `prop`, `propb`, `propbool`                               |
|       `bool` | React PropType Bool Required       | `prop`, `propb`, `propbool`, `propr`                      |
|     `object` | React PropType Object              | `prop`, `propo`, `propobject`                             |
|     `object` | React PropType Object Required     | `prop`, `propo`, `propobject`, `propr`                    |
|       `func` | React PropType Function            | `prop`, `propf`, `propfunc`                               |
|       `func` | React PropType Function Required   | `prop`, `propf`, `propfunc`, `propr`                      |
|     `symbol` | React PropType Symbol              | `prop`, `props`, `propsymbol`                             |
|     `symbol` | React PropType Symbol Required     | `prop`, `props`, `propsymbol`, `propr`                    |
|       `node` | React PropType Node                | `prop`, `propn`, `propnode`                               |
|       `node` | React PropType Node Required       | `prop`, `propn`, `propnode`, `propr`                      |
|    `element` | React PropType Element             | `prop`, `prope`, `propelement`                            |
|    `element` | React PropType Element Required    | `prop`, `prope`, `propelement`, `propr`                   |
| `instanceof` | React PropType InstanceOf          | `prop`, `propi`, `propinstance`, `instance`               |
| `instanceof` | React PropType InstanceOf Required | `prop`, `propi`, `propinstance`, `instance`, `propr`      |
|      `oneof` | React PropType OneOf               | `prop`, `propone`, `proponeof`, `one`                     |
|      `oneof` | React PropType OneOf Required      | `prop`, `propone`, `proponeof`, `one` `propr`             |
|  `oneoftype` | React PropType OneOf               | `prop`, `proponetype`, `proponeoftype`, `onetype`         |
|  `oneoftype` | React PropType OneOf Required      | `prop`, `proponetype`, `proponeoftype`, `onetype` `propr` |
|    `arrayof` | React PropType ArrayOf             | `prop`, `propa`, `proparrayof`, `array`                   |
|    `arrayof` | React PropType ArrayOf Required    | `prop`, `propa`, `proparrayof`, `array`, `propr`          |
|   `objectof` | React PropType ObjectOf            | `prop`, `propo`, `propobjectof`, `object`                 |
|   `objectof` | React PropType ObjectOf Required   | `prop`, `propo`, `propobjectof`, `object` , `propr`       |
|      `shape` | React PropType Shape               | `prop`, `propsh`, `propshape`                             |
|      `shape` | React PropType Shape Required      | `prop`, `propsh`, `propshape` , `propr`                   |

### Redux Functions

|    How | What                               | Alternative keys                                   |
| -----: | ---------------------------------- | -------------------------------------------------- |
| `rstp` | Redux function mapStateToProps     | `map`, `mapToProps`, `propsTo`, `redux`            |
| `rdtp` | Redux function mapDispatchToProps  | `map`, `mapToProps`, `dispatch`, `dispTo`, `redux` |
| `rbac` | Redux bind actions in one function | `bind`, `binda`, `actionc`, `redux`                |

### Global Functions

|   How | What                                                 | Alternative keys |
| ----: | ---------------------------------------------------- | ---------------- |
| `con` | Class constructor calling the super class with props | `constructor`    |

## Release Notes

### 0.3.5

#### Removed

- removed old vsix files

### 0.3.3

#### Added

- Support for typescript
- Changelog

### 0.3.2

Added proptypes for validation
