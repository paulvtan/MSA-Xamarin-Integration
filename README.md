# Additional Features 
## Interaction with a mobile, cross platform app 

<p align="center"><img src="screenshots/xamarin+bot.png" width="400px"/></p>

### Preface

So, you have decided to choose interaction with a mobile, cross platform app as your addition feature. Great choice! Today, we will be looking at how we can integrate your __Microsoft Bot Framework__ with __Xamarin.Forms__ application natively using Direct Line API. Time to take your caht bot on mobile with you with the power of Xamarin!

### Introduction

1. First you need to download the starting base project from this repository here. This is because **Microsoft.Bot.Connector.DirectLine** library that allows us to implement C# classes for using the Bot Framework Direct Line REST API __cannot__ be added to Portable Class Library directly. Therefore for an easier start, we have modified the project properties to target to .NET Platform Standard for you. 

<p align="center"><img src="screenshots/1.PNG"/></p>

&#x26a0; If however the base project doesn't work for you or you would like to start from scratch then follow the steps below.

<!--- Starting from scratch instructions section --->
<details>
  <summary>
    <b> Starting from Scratch </b>
  </summary>
    </br>
    <p align="center"><img src="screenshots/creating_new_project.gif" width="800"/></p>
</details>


