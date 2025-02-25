import React from 'react';
import ImplementationGantt from './components/ImplementationGantt';
import './App.css';

function App() {
  return (
    <div className="App">
      <header className="App-header">
        <h1 style={{ fontSize: '1.5rem', margin: '0.5rem 0' }}>Implementation Planning Tool</h1>
      </header>
      <main>
        <ImplementationGantt />
      </main>
      <footer style={{ textAlign: 'center', margin: '2rem 0', fontSize: '0.8rem', color: '#666' }}>
        © {new Date().getFullYear()} Implementation Planner - All rights reserved
      </footer>
    </div>
  );
}

export default App;
