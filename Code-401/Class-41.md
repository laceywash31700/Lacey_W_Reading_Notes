# Class-41 Reading Notes

## Getting Started with React Native

> 1. ***Name three Core Components of React Native and describe what they do.*** 
> 
```xml
<!-- A container that supports layout with flexbox, style, some touch handling, and accessibility controls -->
<ViewGroup>
<!-- Displays, styles, and nests strings of text and even handles touch events -->
<Text>
<!-- A generic scrolling container that can contain multiple components and views -->
<ScrollView>
```
>
> 2. ***What problem does React Native solve (why call it native)?***

> Developing separate codebases for iOS and Android can be time-consuming and take up resources. Maintenance becomes challenging when changes are needed on both platforms. React Native allows developers to write most of their code in JavaScript and React, and then use that codebase to deploy apps on both iOS and Android. This shared codebase significantly reduces development time and effort.
>

> 3. ***What are the building blocks of a React Native app? How does that compare to a React app?***
> React Native uses components which are the same in both native and react app building but some concepts some concepts like state and props and jsx have slight diffrence that I will not mention here but the major things to look out for I will mention below.

> Navigation is a crucial part of mobile apps, and React Native includes its own navigation system. Commonly used navigation libraries include React Navigation and React Native Navigation. In React, navigation is typically handled by React Router for web applications.

>  While React and React Native both use a style prop to apply styles to components, the way styles are written can differ. In React Native, styles are written using a subset of CSS, but they are translated into native styles. React on the web uses standard CSS for styling.

> React Native allows developers to write native modules in languages like Java, Objective-C, or Swift and bridge them with JavaScript. This enables communication between JavaScript and native code for tasks that require platform-specific functionality. React on the web typically doesn't interact directly with native modules.


## Expo

> 1. ***What solution does expo provide?***

>Expo is a set of tools and services built around React Native that aims to simplify the process of developing and deploying React Native applications. It provides a higher-level abstraction over React Native, making it easier for developers to build mobile applications without needing to delve deeply into the native development aspects. 
>

> 2. ***Expo tries to manage as much of the complexity of building apps as possible, which is why we call it the _*"managed"*_  workflow.***
>
>
> 3. ***What is the difference between React Native and Expo?***

> React Native and Expo are related technologies, but they serve different purposes and offer different features

> Developers using Expo have a quicker setup and can build and deploy apps without dealing with native build configurations. While in contrast, React Native offers two development workflows: the "bare" workflow and the "managed" workflow with managed being a workflow that is primarily provided in expo  abstracting away much of the complexity of native development.

## Expo Snack

> 1. ***Checkout this tool. What does snack allow you to do?***
> It allows you to write and run React Native code directly in your web browser without the need for local development setup
>


## Ejecting

> 1. ***What does “eject” mean within the context of Expo?***
> "Eject" refers to the process of transitioning from the Expo-managed workflow to the standard React Native workflow. 
>

> 2. ***When should you not eject?***

> If your project doesn't require extensive customization of native code or interaction with specific native modules, and the Expo managed APIs cover your needs, then ejecting might introduce unnecessary complexity.
>

> 3. ***Why might you choose to eject?***

> In the Expo managed workflow, the native code for Android and iOS is hidden from the developer. When you eject, you get full visibility and control over the Android and iOS directories in your project. If you need full control over native dependencies and the ability to configure the build process according to your requirements, ejecting is necessary.
>


## Things I want to know about

