# Kuwahara Filter
Kuwahara filter for Unreal Engine 4 and 5 (pics soon).

## ⚙️ Installation

* Download the files and paste them inside your UE project folder
  - For example, you have a UE project named `Kuwahara Filter`
  - Simply paste the `Content` and `Intermediate` folders inside the folder named `Kuwahara Filter` on your drive
* You now have the base material as well as an instance of that material on which you can edit both the x and y radius of the filter
* To use them, create a `Post Process Volume`
* Inside its settings navigate to Rendering Features > Post Process Materials > Array
* Create a new element and select the kuwahara filter material instance
* P.S. if the effect of the filter isn't applied in the entire scene, remember to check `Infinite Extent` in the post process' settings

## 🔑 License

[MIT](https://choosealicense.com/licenses/mit/)

## 🔗 Contact

[@NoxTGM on all socials](https://bento.me/noxtgm)
