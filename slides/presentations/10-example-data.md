Presentation Layouts

# Example: Lists and Code

- No HTML Layout required  
- Simple with markdown
	- just a list
	- followed by a code block

```javascript
const data = {
	nodes: [
		{ id: 'web', label: 'Web Frontend' },
		{ id: 'mobile', label: 'Mobile Device' },
		{ id: 'backend', label: 'Monolith Backend' },
		{ id: 'db', label: 'Database' }
	],
	links: [
		{ source: 'web', target: 'backend' },
		{ source: 'mobile', target: 'backend' },
		{ source: 'backend', target: 'db' }
	]
}
```