# sinatra-rps

<!--Target: http://rps.matchthetarget.com/-->

[Notes for this project are here.](https://learn.firstdraft.com/lessons/99)

Summary of Activities:

- Review the structure of the project. It contains:
  - app.rb
  - Gemfile
  - views/layout.erb
  - config/environment.rb
  - bin/dev, bin/setup, etc.
  - spec/ - includes automated tests

- Run the app from the terminal with bin/dev and preview the web page. I see the following message:

```
Welcome to your Sinatra App!

Define some routes in app.rb
```

- To execute automated test, type rake grade.

- When using a quote within a quote precede it with a backward slash, e.g., From <a href=\\"https://en.wikipedia.org/wiki/Rock_paper_scissors\\" target=blank>Wikipedia</a>.

- Create the hyperlinks within the views folder. All files must have the extension .erb and can be called with, e.g.:

```
get("/rock") do
  erb(:rock)
end
```

- Initially, I named the files with extension .html, and I had to call the files differently with.

```
get("/rock.html") do
  #File.read('views/rock.html')
  erb(:rock)
end
```

- Within the erb file, populate it with html code, nonetheless.

- Compare the result with: <a href="http://rps.matchthetarget.com" target=_blank>http://rps.matchthetarget.com</a>
