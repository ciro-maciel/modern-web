## Redux
- [Redux](http://redux.js.org/)
- [Build A React App With Redux](https://egghead.io/courses/build-a-react-app-with-redux)
- [Curated tutorial and resource links I've collected on React, Redux, ES6, and more](https://github.com/markerikson/react-redux-links)
- [A categorized list of Redux-related addons, libraries, and utilities](https://github.com/markerikson/redux-ecosystem-links)
- [Getting Started with Redux](https://egghead.io/courses/getting-started-with-redux)
- [Building React Applications with Idiomatic Redux](https://egghead.io/courses/building-react-applications-with-idiomatic-redux)
- [10 Tips for Better Redux Architecture](https://medium.com/javascript-scene/10-tips-for-better-redux-architecture-69250425af44)
- [Awesome React / Redux boilerplate and tutorial](https://github.com/buckyroberts/React-Redux-Boilerplate)
- [A cartoon intro to Redux](https://code-cartoons.com/a-cartoon-intro-to-redux-3afb775501a6)
- [React JS / Redux Tutorials](https://www.youtube.com/playlist?list=PL6gx4Cwl9DGBbSLZjvleMwldX8jGgXV6a)
- [Redux Tutorials](https://www.youtube.com/playlist?list=PLoYCgNOIyGADILc3iUJzygCqC8Tt3bRXt)
- [DevTools for Redux](https://github.com/gaearon/redux-devtools)
- [Time Travel in React Redux apps using the Redux DevTools](https://onsen.io/blog/react-redux-devtools-with-time-travel/)

## Redux Form
- [Abstracting Form State with Redux Form](https://www.youtube.com/watch?v=eDTi7lYR1VU)
- [Redux Form Submit To Server With Redux Observable](https://www.youtube.com/watch?v=JT2F2NQ19o0)
- [Add more recipes](https://github.com/redux-observable/redux-observable/issues/87)
- [Question: Integration with redux-form](https://github.com/redux-saga/redux-saga/issues/161#issuecomment-191312502)
- [How to handle async update onUpdate of each field and keep ids using redux-form and redux-observable](https://github.com/erikras/redux-form/issues/3215)
- https://github.com/reactjs/react-redux/blob/master/docs/api.md#connectmapstatetoprops-mapdispatchtoprops-mergeprops-options
- http://redux.js.org/docs/basics/UsageWithReact.html#containersfilterlinkjs
- http://redux-form.com/7.0.3/examples/remoteSubmit/ 
- http://redux-form.com/7.0.3/examples/selectingFormValues/
- http://redux-form.com/7.0.3/docs/api/ReduxForm.md/
- https://github.com/erikras/redux-form/issues/1385
- https://github.com/reactjs/react-redux/blob/master/docs/api.md#connectmapstatetoprops-mapdispatchtoprops-mergeprops-options
- https://github.com/erikras/redux-form/issues/3215
- [Submit a form when user press enter](https://github.com/erikras/redux-form/issues/572)

## Redux Observable
// In redux-observable your epics receive a stream of all actions dispatched--what may not be obvious is that includes actions dispatched by other epics. 
// This is a very powerful feature because you can write epics that don't need to be coupled to implementation details in the other epics. The action 
// is the contract.

- https://egghead.io/courses/up-and-running-with-redux-observable
- https://stackoverflow.com/questions/45852079/use-one-output-of-epic-as-another-input-of-epic-in-react-observable
- https://medium.com/kevin-salters-blog/epic-middleware-in-redux-e4385b6ff7c6
- https://stackoverflow.com/questions/45194869/how-to-handle-async-update-onupdate-of-each-field-and-keep-ids-using-redux-form
- https://github.com/prescottprue/react-redux-firebase/blob/master/docs/recipes/redux-form.md
- https://redux-observable.js.org/docs/basics/Epics.html
- https://redux-observable.js.org/docs/recipes/Cancellation.html
- https://github.com/este/este/blob/master/epics/auth.js#L34
- https://medium.com/kevin-salters-blog/epic-middleware-in-redux-e4385b6ff7c6
- https://medium.com/kevin-salters-blog/writing-epic-unit-tests-bd85f05685b
- http://reactivex.io/rxjs/class/es6/Observable.js~Observable.html
- https://stackoverflow.com/questions/35411423/how-to-dispatch-a-redux-action-with-a-timeout/35415559#35415559
- https://stackoverflow.com/questions/34570758/why-do-we-need-middleware-for-async-flow-in-redux/34599594#34599594
- https://github.com/redux-observable/redux-observable/issues/33
- https://www.robinwieruch.de/redux-observable-rxjs/
- https://github.com/rwieruch/react-redux-soundcloud/blob/master/extension-observable/src/actions/auth.js
- https://medium.com/kevin-salters-blog/epic-middleware-in-redux-e4385b6ff7c6
- https://github.com/este/este/blob/master/epics/auth.js#L34
- https://github.com/Reactive-Extensions/RxJS-DOM/blob/master/doc/operators/getjson.md
- https://github.com/Reactive-Extensions/RxJS-DOM/blob/master/doc/operators/post.md
- https://developer.mozilla.org/pt-BR/docs/Web/HTTP/Controle_Acesso_CORS


// https://redux-form.com/7.0.4/docs/faq/howtoconnect.md/
// https://stackoverflow.com/questions/39419237/what-is-mapdispatchtoprops


// https://www.npmjs.com/package/rxjs
// http://reactivex.io/rxjs/
/import {
    Observable
} from 'rxjs/Observable';
import 'rxjs/add/observable/dom/ajax';
import 'rxjs/add/operator/catch';
import 'rxjs/add/operator/skip';
import 'rxjs/add/operator/debounceTime';
import 'rxjs/add/operator/map';
import 'rxjs/add/operator/do';
import 'rxjs/add/operator/filter';
import 'rxjs/add/operator/mergeMap';
import 'rxjs/add/operator/startWith';


// https://redux-observable.js.org/docs/basics/Epics.html
// https://github.com/ReactiveX/rxjs/issues/1694
// https://redux-observable.js.org/docs/recipes/Cancellation.html
// https://github.com/este/este/blob/master/epics/auth.js#L34
    // https://github.com/Reactive-Extensions/RxJS-DOM/blob/master/doc/operators/getjson.md
    // https://github.com/Reactive-Extensions/RxJS-DOM/blob/master/doc/operators/post.md
    // https://developer.mozilla.org/pt-BR/docs/Web/HTTP/Controle_Acesso_CORS

