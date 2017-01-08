# vue-sublime-snippets
Simplify and supercharging my workflow with snippets for Vue.js that help me spin things up quickly

Not all of the files here are precisely for Vue development (such as the gitignore), but all can be applied to Vue workflows.

Any files that are specifically vue-related begin with a 'v'.

##Usage
Place the files enclosed that end with the `.sublime-snippet` extension in your Sublime User folder. Typically, this will exist at pwd `~/Library/Application Support/Sublime Text 3/Packages/User`, but will be applied correctly wherever `Sublime Text (version)/Packages/User` is found

Basic setup for the snippets are as follows:
```<snippet>
	<content><![CDATA[
snippet code goes here
]]></content>
	<!-- Optional: Set a tabTrigger to define how to trigger the snippet, you can change this if you'd like a different trigger because naming -->
	<tabTrigger>vkeep</tabTrigger>
	<!-- Optional: Set a scope to limit where the snippet will trigger, not defined in any snippet but left commented here in case you want to use it -->
	<!-- <scope>source.python</scope> -->
</snippet>```