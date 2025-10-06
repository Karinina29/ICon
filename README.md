import React from 'react';
import AccountBalanceIcon from '@mui/icons-material/AccountBalance';
import { Button } from '@mui/material';

function App() {
  return (
    <div style={{ textAlign: 'center', marginTop: '50px' }}>
      <AccountBalanceIcon style={{ fontSize: 60, color: '#1976d2' }} />
      <h2>Banco</h2>
      <Button variant="contained" color="primary">
        Acción
      </Button>
    </div>
  );
}

export default App;
