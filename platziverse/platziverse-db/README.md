# platziverse-db

## usage

´´´ js
const setupDataBase = require('platziverse-db)

setupDataBase(config).yhen(db => {
    const { Agent, Metric } = db
}).catch(err => console.error(err))

´´´