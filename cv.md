## Shulika Ruslan

### Contacts:

- skype: rufunt
- telegram: @rufunt
- github

### My goal:

- work junior frontend developer;

### Basic skills:

- Ruby, JS, vue.js, html, css, git;

### Code:

```
methods: {
        startGame: function() {
            this.gameIsRunning = true
            this.playerHealth = 100
            this.monsterHealth = 100
            this.turns = []
        },
        attack: function() {
            let damage = this.calculateDamage(3,10)
            this.monsterHealth -= damage
            this.turns.unshift({
                isPlayer: true,
                text: 'Player hits Monster for ' + damage
            })
            if (this.checkWin()) {
                return
            }
            this.monsterAttacks()
        },
      }
```

### Education:

- higher education: Donetsk National Technical University;

### Level of english:

- Elementary;
