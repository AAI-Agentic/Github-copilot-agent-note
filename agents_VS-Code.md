# Work with agents in VS Code

* Tutorial: Work with agents in VS Code
https://code.visualstudio.com/docs/copilot/agents/agents-tutorial


Open the project folder in VS Code.

Open the Chat view (⌃⌘I) and select Agent from the Agents dropdown.

Optionally, choose a specific language model if you have a preference.

Important
If you don't see the agent option, make sure agents are enabled in your VS Code settings
```yml
chat.agent.enabled
```

Enter the following prompt in the chat input field to scaffold the todo app and select Send.

```javascript
Create a simple todo app with HTML, CSS, and JavaScript. Include an input field to add todos, a list to display them, and a delete button for each item.
```

https://code.visualstudio.com/assets/docs/copilot/agents-tutorial/local-agent-todo-app-scaffold-v2.mp4

ou can preview the changes in the integrated browser.

Enable the integrated browser for localhost URLs by configuring 
```yml
workbench.browser.openLocalhostLinkse
```

Open the index.html file and select the Preview button.
