const express = require('express');
const app = express();
const port = 3000;

app.get('/', (req, res) => {
  res.send('ぽんた式診察室へようこそ🍮');
});

app.get('/health', (req, res) => {
  res.status(200).send('OK');
});

app.listen(port, () => {
  console.log(`診察室がポート${port}で開業中！`);
});