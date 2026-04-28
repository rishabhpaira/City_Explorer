# Code Citations

## License: unknown
https://github.com/jtessieau/todo-list/blob/9a8c8f1a85c97efc812b7bc50900bf7c21e0eae0/backend/api/v1/middlewares/auth.js

```
require('jsonwebtoken');

const authMiddleware = (req, res, next) => {
  const token = req.header('Authorization')?.replace('Bearer ', '');

  if (!token) {
    return res.status(401).json({ message: 'No token provided' });
  }

  try {
    const decoded = jwt.verify(token, process.env.JWT_SECRET);
    req.user = decoded;
    next();
  } catch (error) {
    res.status(401).json({ message: 'Invalid token' });
  }
```


## License: unknown
https://github.com/PrinceBrown/ownr/blob/8777d7d0014119fb2e3208c458cdb38328a05d4d/server/config/auth/authWithJWT.js

```
require('jsonwebtoken');

const authMiddleware = (req, res, next) => {
  const token = req.header('Authorization')?.replace('Bearer ', '');

  if (!token) {
    return res.status(401).json({ message: 'No token provided' });
  }

  try {
    const decoded = jwt.verify(token, process.env.JWT_SECRET);
    req.user = decoded;
    next();
  } catch (error) {
    res.status(401).json({ message: 'Invalid token' });
  }
```


## License: unknown
https://github.com/YordiYach/backendcine/blob/778750e076b6b41654f283ae4d5651164d273b84/middlewares/authMiddleware.js

```
require('jsonwebtoken');

const authMiddleware = (req, res, next) => {
  const token = req.header('Authorization')?.replace('Bearer ', '');

  if (!token) {
    return res.status(401).json({ message: 'No token provided' });
  }

  try {
    const decoded = jwt.verify(token, process.env.JWT_SECRET);
    req.user = decoded;
    next();
  } catch (error) {
    res.status(401).json({ message: 'Invalid token' });
  }
```


## License: unknown
https://github.com/OSAMA-tec/EZIPOS/blob/e92ac7d077a9acda162eada77a6abb5b488e43f7/middleware/authMiddleware.js

```
require('jsonwebtoken');

const authMiddleware = (req, res, next) => {
  const token = req.header('Authorization')?.replace('Bearer ', '');

  if (!token) {
    return res.status(401).json({ message: 'No token provided' });
  }

  try {
    const decoded = jwt.verify(token, process.env.JWT_SECRET);
    req.user = decoded;
    next();
  } catch (error) {
    res.status(401).json({ message: 'Invalid token' });
  }
```


## License: unknown
https://github.com/Bilal-Gujjar/node-app/blob/aaf0ebf21032d149266c02e3c9b11e363dc27e5e/src/middleware/authmiddleware.js

```
require('jsonwebtoken');

const authMiddleware = (req, res, next) => {
  const token = req.header('Authorization')?.replace('Bearer ', '');

  if (!token) {
    return res.status(401).json({ message: 'No token provided' });
  }

  try {
    const decoded = jwt.verify(token, process.env.JWT_SECRET);
    req.user = decoded;
    next();
  } catch (error) {
    res.status(401).json({ message: 'Invalid token' });
  }
```


## License: unknown
https://github.com/UsmanMalikk/POS-Backend/blob/b6b3791d24c2686a8f886fb947692fa18dc8bff6/src/middleware/authMiddleware.js

```
require('jsonwebtoken');

const authMiddleware = (req, res, next) => {
  const token = req.header('Authorization')?.replace('Bearer ', '');

  if (!token) {
    return res.status(401).json({ message: 'No token provided' });
  }

  try {
    const decoded = jwt.verify(token, process.env.JWT_SECRET);
    req.user = decoded;
    next();
  } catch (error) {
    res.status(401).json({ message: 'Invalid token' });
  }
```

