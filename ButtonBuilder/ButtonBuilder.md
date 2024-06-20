* **ButtonBuilder**
```typescript
import { ButtonBuilder, ButtonStyle } = 'discord.js'

const confirm = new ButtonBuilder() // ButtonFunction
    .setCustomId('test_button')     // ButtonID
    .setLabel('Test')               // ButtonTitle

    .setStyle(ButtonStyle.Danger);     // ButtonBuilder Options
    .setURL('https://discord.js.org'); // ButtonBuilder Options
    .setDisabled(true);                // ButtonBuilder Options
    .setEmoji('123456789012345678');   // ButtonBuilder Options
```
