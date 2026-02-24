# Kuwahara Filter

Adjustable Kuwahara filter effect for Unreal Engine's post process component.

> [!CAUTION]
> Should work in both Unreal Engine 4.X and, as far as I'm aware, 5.X (if not please contact me).

## 📖 Installation

* Download the files and paste them inside your UE project folder
  - For example, let's say you have a UE project named `Kuwahara Filter`
  - Simply paste the downloaded `Content` and `Intermediate` folders inside the folder named `Kuwahara Filter` on your hard drive
* You now have the base material as well as an instance of that material on which you can edit both the x and y radius of the filter
* To use them, create a `Post Process Volume`
* Inside its settings navigate to `Rendering Features > Post Process Materials > Array`
* Create a new element and select the kuwahara filter material instance

> [!NOTE]
> If the effect of the filter isn't applied in the entire scene, remember to check `Infinite Extent` in the post process' settings.

## 📄 License

[MIT License](https://choosealicense.com/licenses/mit/)

<br>

<a href="https://ko-fi.com/noxtgm" target="_blank" rel="noreferrer"><img src="https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExOG00a3RqYTBzcmo2a2UxZGZ6bXl2dDY5Z2w0YmQ0Y2RxMWd0aWM4OSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/bZgsAwXUIVU2tcKn7s/giphy.gif" alt="Support me on Ko-fi" width="240" height="55"/></a>
