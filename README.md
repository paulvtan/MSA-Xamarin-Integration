# Additional Features 
## Interaction with a mobile, cross platform app

### Preface

So, you have decided to choose interaction with a mobile, cross platform app as your addition feature. Great choice! Today, we will be looking at how we can integrate your chat bot with __Xamarin.Forms__ application natively. Time to take your bot on mobile with you with the power of Xamarin!

### Introduction

First you need to download the starting base project from this repository here. This is because **Microsoft.Bot.Connector.DirectLine** library that allows us to implement C# classes for using the Bot Framework Direct Line REST API __cannot__ be added to Portable Class Library directly, therefore we have modified the project properties to target to .NET Platform Standard for you. 

<img src="screenshots/1.PNG"/>

