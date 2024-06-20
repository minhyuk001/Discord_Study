* **ButtonColor**
  * **`ButtonStyle.Primary` = `Blue`**
  * **`ButtonStyle.Secondary` = `Gray`**
  * **`ButtonStyle.Success` = `Green`**
  * **`ButtonStyle.Danger` = `Red`**
* **ButtonLink**
  * **`ButtonStyle.Link` = `URL`**
 
* **ButtonStyle Use Ex**
```typescript
const button = new ButtonBuilder()
	.setLabel('Title')
	.setStyle(ButtonStyle.(ButtonColor or ButtonLink));
```
