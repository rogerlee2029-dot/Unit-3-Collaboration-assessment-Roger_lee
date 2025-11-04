
Welcome to **TreeLife**, your guid about the beauty , diversety , and importance of trees around the world.

---
## About Us
At **TreeLife**, we're passionate about forests and green living. 
Our mission is to:

- Educate people about the different types of trees.

- Promote sustainable forestry.
- Encourage reforestation projects.
> "The best time to plant a tree was 20 years ago. The second best time is now."  
— *Chinese Proverb*
___
## **Featured Trees**
### Oak Tree 
**Scientific name**: *Quercus robur*

Known for its strength and longetivity, the oak is a symbol of endurance.
![rah](https://orleansconservationtrust.org/wp-content/uploads/image-152-400x300.jpeg)
___
### **Pine Tree**
**Scientific Name**:*Pinus*

Evergreen and aromatic, pine trees thrive in colder regions.
![rano.2](https://www.sciencing.com/sciencing/do-pine-trees-need-survive-6549613/c64512e361624e3d9a21ffc39aed7f5c.jpg)
___
## **Tree Identification Tool**
You can use this simple **Javascript** function to identify a tree by it characteristics :

```Javascript
function identify_tree(leaf_shape, region){
    if (leaf_shape == "needle" && region == " cold "){
        return "Pine Tree"
    } else if(leaf_shape == "broad" && region == "temperate"){
        return "Oak Tree"
    } else {
        return "Unknown Tree"
    }
}
console.log(identify_tree("needle", "cold"))
```
