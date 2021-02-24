You probably shouldn't. 

No, seriously. I mean unless you've dedicated your whole life to studying wheel
physics (a branch of classical mechanics), you're usually going to be costing 
more than you're benefiting. For example, if you have an electric car startup 
then you're not going to hire a whole development team for the tires, or spend 
two years of your valuable time to dabble in the commercial tire R&D game. 
Realistically, you're probably going to go with something like Michelin or 
Firestone because that's kind of their thing, and tires aren't really your 
thing (because electric cars are your thing). 

As long as we all agree on that...

How to include native dependencies in your Mendix app:
1. Use react-native community libs and open source libs (npm modules)
2. Use native libs ("Cocoa Pods" for iOS/"Java packages" for Android) 
3. Create your own native libs in combination with 
react-native Native Modules in order to expose an interface to a client app's javascript runtime. 
(i.e. call native code using javascript source) 
From there, the javascript runtime will call a special kind of npm module meant to implement the 
called function in native code. 

What is native code you say? Well that's a separate discussion for a separate Markdown file (:

