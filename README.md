## Spanish Wordle Hack

### Game URL
https://wordle.danielfrg.com/

### How to use and run the script
1. Open index.js and modify the rules:
```
const LENGTH = 5
const INCLUDES = 'coa'
const EXCLUDES = 'etuipsghjlbm'
const MATCH = 'c____'
```
2. Run the script
```
node index.js
```
3. An output of word matches should be shown
```
[
  'cacao', 'cando', 'canoa', 'canon',
  'carao', 'cardo', 'caron', 'carro',
  'cavon', 'cazon', 'cañon', 'coana',
  'cocad', 'cocan', 'cocar', 'cofan',
  'conca', 'coona', 'corad', 'coran',
  'corar', 'corca', 'corda', 'corra',
  'corva', 'corza', 'covad', 'covan',
  'covar', 'coyan', 'coñac', 'croad',
  'croan', 'croar', 'croza'
]
```