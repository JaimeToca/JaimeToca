**@Composable**  
**fun Greeting()** {    
&nbsp;&nbsp;Column (modifier = Modifier.padding(16.dp)) {  
&nbsp;&nbsp;&nbsp;&nbsp;Text("**Hola 👋, I'm Jaime"**, style = typography.h4)    
&nbsp;&nbsp;&nbsp;&nbsp;Text("Based in Madrid 🐻")  
&nbsp;&nbsp;&nbsp;&nbsp;Text("Speak 🇺🇸 🇪🇸")     
&nbsp;&nbsp;&nbsp;&nbsp;Text("Love ☕ , 🎮, 📖, 🐶, :airplane:")  
&nbsp;&nbsp;&nbsp;&nbsp;Text("Love 🇵🇪 food")  
&nbsp;&nbsp;}  
**}**

**@Composable**    
**fun LatestArticles()** {      
&nbsp;&nbsp;Column {      
&nbsp;&nbsp;&nbsp;&nbsp;Text("[Deploying to Firebase Test Lab from your Docker container](https://www.jaimetoca.com/docker-firebase-testlab-gcloud/)")    
&nbsp;&nbsp;&nbsp;&nbsp;Text("[Finding the right Docker image for unit and UI tests](https://www.jaimetoca.com/docker-android-espresso-unit-test/)")    
&nbsp;&nbsp;}  
**}**

**@Composable**   
**fun DefaultPreview()** {  
&nbsp;&nbsp;BasicsGithubTheme {  
&nbsp;&nbsp;&nbsp;&nbsp;Greeting()  
&nbsp;&nbsp;&nbsp;&nbsp;LatestArticles()  
&nbsp;&nbsp;}  
**}**

<!--
**JaimeToca/JaimeToca** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
### Hola 👋
-->
