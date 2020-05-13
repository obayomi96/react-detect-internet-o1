# react-detect-internet

### Usage

`npm install react-detect-internet`

```
import DetectInternet from 'react-detect-internet';

const App = () => {
  return (
    <div>
      <DetectInternet />
      Home page
    </div>
  );
}

export default App;
```

### props
- message: String to display in text e.g 'Connection lost, please check internet'
- style: Custom style

### Author
- Martins Obayomi

### Todo
- Refactor Webpack to work as a JS library (add peerDependencies)
- Setup test with travis, circleci and add coverage badges
- Write test and maintain 99% and above
- Write more features like routing etc.. that users can get by simply passing a prop
