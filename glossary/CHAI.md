# Chai

[Chai](http://chaijs.com/) — это BDD/TDD assertion-библиотека для [Node.js](NODEJS.md) и браузеров. Обычно используется вместе с фреймворками для тестирования, такими как, например, [Mocha](MOCHA.md).

Одной из особенностей данной библиотеки является возможность писать утверждения (assertions) не только в классической форме: `assert.typeOf(foo, 'string')`, но и в «цепочечной», что позволяет формулировать утверждения в более естественной, удобной и выразительной манере: `expect(foo).to.be.a('string')`.