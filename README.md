## D3 Binary Search Tree


A library to create tree visualizations in the browswer using D3 and javascript. 


### Getting started


The library takes as input:
* an element ID to place the visualization.
* a nested parent-child datastructure. 

Node-link data (node, link [sourceNode, targetNode] can be converted to a 
nested representation using the [treemill](https://www.npmjs.org/package/treemill) library.

### A Sample Tree

<img align="middle" src="http://38.media.tumblr.com/4f4d74682a856736f9e9d2d5779a7b33/tumblr_n8qa6dyZ071twn317o1_1280.png" width="450px" />


The data used in the tree above looks like: 

```
  { 
    "name":"Steve", 
    "children": [ 
      {
        "name":"Dahlia",
        "children": [
          { 
            "name":"Boris",
            "children": []
          }, 
          { 
            "name":"Natasha",
            "children": [
              { 
                "name":"Leo",
                "children": [
                  {
                    "name":"Lena",
                    "children": []
                  },
                  {
                    "name":"Ralph",
                    "children": [
                      { 
                        "name":"Meghna",
                        "children":[]
                      }
                    ]
                  }
                ]
              }
            ]
          }
        ]
      }
    ]
  }


```
