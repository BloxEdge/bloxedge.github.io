# Getting Started

Welcome to BloxEdge! To get started, you'll first need our Edgerunner CLI.

In this Getting Started introduction, you'll learn how to:
- Install the Edgerunner CLI
- Signup to BloxEdge
- Create your first BloxEdge script
- Deploy your script
- Connect to your script logs

1. Installing the Edgerunner CLI

We'll be using the Edgerunner CLI throughout this introduction to login, deploy scripts, and check on our logs.

```
<this should probably come from brew or something>
```

2. Signup to BloxEdge

This next command will open your browser to sign into the CLI using an auth provider of your choice.

```
edgerunner signup
```

3. Create your first BloxEdge script

Now we can create our first script. We suggest you start from one of our starter templates.

```
edgerunner create <something> -o ./<my_script>
```

You can inspect the default Script Info generated for your script by checking its `toml` file in its output directory.
It should look something like this:

```
<example scriptInfo>
```
4. Deploy your script

Once you're script is ready, you can deploy this to a BloxEdge server with the command:

```
edgerunner deploy <url> <script-directory>
```
Congratulations, your first script should be running live! To see it in action, follow the URL output by the script.

5. Connect to your script logs

Now that your script is live, you can monitor it in real-time<sup>*</sup>. The following command opens a connection between a scripts logs, and your shell:

```
edgerunner observe <url> <script-id>
```

Remember to keep this connection open to observe logs in real-time. To terminate, simply C-c or close your shell.


Now that your scripts are live on BloxEdge, they're ready to be used in your experiences! The following examples can help to supercharge your experiences even faster:
