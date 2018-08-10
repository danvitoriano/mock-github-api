# mock-github-api

Fork from [https://github.com/mzabriskie/mock-github-api](https://github.com/mzabriskie/mock-github-api)

Quick and dirty mock API server for Github since we hit rate throttling at our workshop 😄

## Getting started

```bash
git clone https://github.com/mzabriskie/mock-github-api.git
cd mock-github-api
npm install
npm start
```

## API Requests

- users
- repositories
- orgs
- repositories starred by user
- `/user not found` to get 404 error
- `/limit requests` to get 403 forbidden


## License

MIT
