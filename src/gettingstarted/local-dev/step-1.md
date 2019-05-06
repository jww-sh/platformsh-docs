<html>
<head>
  <link rel="stylesheet" type="text/css" href="/asciinema/asciinema-player.css" />
  <script src="/asciinema/asciinema-player.js"></script>
</head>
</html>

# Local development

## Download the code

If you have already [pushed your code](/gettingstarted/own-code.md) to Platform.sh, then you should already have a local repository that you can build from.

Otherwise, it will be necessary to download a local copy of your project first.

1. **Get project ID**

    You will need the id of your project. You can retrieve this id at any time using the CLI commands `platform` or `platform project:list`.
    
    {% asciinema_local %}/asciinema/recordings/list-projects.cast{% endasciinema_local %}

2. **Get a copy of the repository locally**

    {% asciinema_local %}/asciinema/recordings/local-copy.cast{% endasciinema_local %}
    
    Next, use the CLI to download the code in your Platform.sh project using the command
    
    ```bash
    platform get <project id>
    ```

Now that you have a local copy of your application that is configured to the Platform.sh remote repository, you can now connect to its services and build it on your machine.

<html>
<head>
<link rel="stylesheet" href="/styles/styles.css">
</head>
<body>

<br/><br/>

<center>

<a href="/gettingstarted/local-dev.html" class="buttongen small">Back</a>
<a href="/gettingstarted/local-dev/step-2.html" class="buttongen small">I have a copy of my code locally</a>

</center>

<br/><br/>

</body>
</html>
