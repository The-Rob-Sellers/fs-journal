# MVC
5/8/23
Observer patterns
appState.on("values", _draw);
_draw() - subscibing to the changes in data; so that I can draw when needed
![Alt text](../../../../OneDrive/Documents/CodeWorks/study%20guides/MVCS.jpg)
5/9/23
MVC process steps:
Model = bluebrints, start there!
1. create .js files in Models (Gachamon name for Gachamon class)
2. export class (eg Gachamon) at the top of each file before defining it. example:
export class House{...

3. constructor is what is invoking the class, needs () example:
{ walls: 'plywood', floors: 'tile', windows: 'glass'}
constructor (walls, floors, windows) {
    this.walls = walls
    this.floors = floors
    this.windows = windows
}
}
4. new House:
    new House({ walls: 'plywood', floors: 'tile', windows: 'glass'})
    new House({ walls: 'sheetrock'...etc})
5. create new AppState file - use class to construct
6. create new service file - use for data manipulation
Don't export whole file, make a single instance of a class for a single need and export as a const:
export const gachamonService = new GachamonService()
7. create new file in controller = "setting up" the controller
basically a "filter layer" between code and user
User must have access to controller!!!!!!!!!!!
App.js has been created as a window between my HTML (the user) and the REST OF MY JS
***MUST export controller*** "mount" upon page load
export class GachamonController {
    constructor() {
console.log('hello from GM controller')
    }
}
***MUST tell the app.js to run controller***
Make sure console log works before moving on!
8. HTML draw to page....copy to add to model!
selectable class highlights element and title tag in element states what's in quotes on hover
9. back to the model with the HTML code! getter function:
get ListTemplate() {
    return
    <div classs='col-1 selectable'>...
}
10. declare function outside of class - user doesn't need access to this whole page, only focus on what they need - then add draw to the constructor function:
let gachamon = appState.gachamon
gachamon[0].
***Changing the DOM happens in the controller***
@type  {import('./Models/Gachamon').Gachamon[]} 
gachamon.forEach(g => template += g.ListTemplate)\
11. create observers to draw updates on any changes madde to the Appstate

5/10/23
