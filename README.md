# lhltutorials
This is an intro to a few workflow tools, frameworks and libraries that CAN be useful in making you a more 
productive front end dev. 

There are many tools, frameworks and libraries. These are simply some of the ones that I use. The most important
thing to take away from this is that if you find yourself doing anything repetitive, someone has probably come up with a smart way to make your life easier. 

[Spectacle App](https://www.spectacleapp.com/)
This is a window manager for mac. Pain point - resizing and toggling your windows with a mouse is slow, and you never really make the most of the space. 
Spectable decreases window resize time by an order of magniture. This can literaly save you an hour or two per day. 

[Alfred](https://www.alfredapp.com/) Alfred is like finder and spotlight had a kid and pumped it full of steroids. [Good article from a Canadian about Alfred](https://medium.com/@rurka/kill-the-dock-for-macos-dcb1d4ba8c8c)

[Next.js](https://github.com/zeit/next.js/) Create-react-app is amazing for rapid prototyping of a component or a series of components. But there are some things that create-react-app doesn't do out of the box. 

Code splitting, routing out of the box, static exports AKA no node instance. Dynamic imports at the component level. HOWEVER since next is a bit bleeding edge there are some compatability issues. 

Warning combining dynamic imports and static exports can cause your app to disappear into pure energy. 

Finally material-ui. 
```
create-react-app material-demo
cd material-demo
yarn start
```
Now lets add in everything we need to get material ui working 

```
yarn add material-ui
yarn add react-tap-event-plugin

Glamorous. Pain point that it solves. Gives you a clean way to wrap your styling into a component and recycle. 
It's nice once you are thinking in the react idea of components, to stop trying to use a document model and selectors to manage styling. What works better is 
Alternatives: LESS, SASS, Radium, styled-components. 

