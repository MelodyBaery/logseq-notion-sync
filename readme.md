[中文文档](./README_CN.md)

- # logseq-notion-sync [[2023-05-20 Saturday]]
	- This plugin helps you synchronize Logseq content with [Notion](https://notion.so/).
- ## Features
	- Headings
	- Linked text
	- Todo items
	- Code blocks
	- Block quotes
	- Tables
- ## Usage
	- For the initial setup, please provide your `Notion API key` and `Page ID`
		- Get `Notion API key` from this link: https://www.notion.so/my-integrations
		- Get `Page ID` from this link: https://developers.notion.com/docs/working-with-page-content#creating-a-page-with-content
		- Notice: `Add connections`
			- ![Add connections](./add_connections.png)
	- To sync the content of the current block to Notion, type the slash command: `sync block to notion`
	- To sync the entire page containing the current block to Notion, type the slash command: `sync page to notion`
- ## Demo
	- ![demo](./logseq-to-notion.gif)
- ## License
	- [MIT](https://choosealicense.com/licenses/mit/)
