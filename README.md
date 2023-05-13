# import logo from './logo.svg';
import './App.css';
function MyButton() {
  function handleClick() {
    alert ("Hörrö kan du inte läsa eller???");
  }

  return (
    <button onClick={handleClick}>Klicka inte</button>
  );   
}
function App() {
  return (
   <div className="App">
      <header className="App-header">
        <img src={logo} className="App-logo" alt="logo" />
        <p>
          Tjenis <code>klenis</code> and save to reload.
        </p>
        <a
          className="App-link"
          href="https://reactjs.org"
          target="_blank"
          rel="noopener noreferrer"
        >
          Hej
        </a>
        <MyButton></MyButton>   
      </header>
    </div>
  );
}

export default App;
