### Support the creator of the course John Smilga from [udemy](https://www.udemy.com/share/10452m3@nOO3G9wo56HD4dZ5XNGkx7770JayEO1jtWpyN_iLX6mUysWOLglQDV08P_WEZAeEhA==/)

#### Netlify TOML for create-react-app

[build]

- command = 'npm run build'
- publish = '/build'
- functions = './functions'

[[redirects]]

- from = '/api/\*'
- to = '/.netlify/functions/:splat'
- status = 200

[[redirects]]

- from = '/\*'
- to = '/index.html'
- status = 200

#### build Command

"build": "CI= react-scripts build"
