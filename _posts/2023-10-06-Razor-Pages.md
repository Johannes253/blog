---
layout: post
title: "Razor Pages"
author: Johannes Mayrhofer
---

To be honest, nothing of this tutorial was easy, to start of CTRL+F5 didn't work, at all, had to follow a Youtube tutorial on how to change this. After using this command: dotnet aspnet-codegenerator razorpage -m Movie -dc RazorPagesMovie.Data.RazorPagesMovieContext -udl -outDir Pages/Movies --referenceScriptLibraries --databaseProvider sqlite, i had quite a lot of errors i had to fix. I had to restart my computer for this to work. The next thing was that it didn't populate my database, after several restarts it finally did, even though I didn't change anything. The same thing happened to me with the Database, in the step where i needed to update the database, I had to restart my computer. I can attribute most of those to just having a european computer, which might explain some of the things, but the last thing was something else. When i added limitations for the different fields in the Movie Model, the seed got an error, it tried casting form an int to a decimal, even though both values were decimals. I tried everything, it didn't even work after restarting, what helped was I had to get the project from Github again.

The parallels would be that both take content and use templates to display them. The differences is that Jekyll is static data while Razor is more dynamic (can edit and change stuff).

Even though it was very frustrating, I feel like I have learned a lot and feel very confident that i can make more Razor Pages in the future.

<div style="clear:both;"></div>

