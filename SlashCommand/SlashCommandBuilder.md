```typescript
const command = new slashcommandbuilder()
  .setName('Ping')
  .setDescription('Say Ping !')

const builder = new slashcommand(command, function (bot,interaction) {
  interaction.reply('pong')
)}
```
