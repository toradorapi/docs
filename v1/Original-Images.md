# Original Images
## [GET] /api/v1/img_original/:character
Shows a random image of the specified character.
### Parameters
| Parameter  | Description                                                  | Example |
|------------|--------------------------------------------------------------|---------|
| :character | The character you want an image of (`all` for any character) | taiga   |
### Result
```json
{
  "url": "https://vignette.wikia.nocookie.net/tora-dora/images/6/6e/E3_-_35.png/revision/latest?cb=20160501212414",
  "source": "tora-dora.fandom.com",
  "status": "success"
}
```

## [GET] /api/v1/img_original/:character/list
Shows all images of the specified character.
### Parameters
| Parameter  | Description                                                  | Example |
|------------|--------------------------------------------------------------|---------|
| :character | The character you want an image of (`all` for any character) | taiga   |
### Result
```json
{
  "status": "success",
  "list": [
    {
      "url": "https://vignette.wikia.nocookie.net/tora-dora/images/1/18/Screenshot_2.png/revision/latest?cb=20160325110928",
      "source": "tora-dora.fandom.com"
    },
    {
      "url": "https://vignette.wikia.nocookie.net/tora-dora/images/d/db/Screenshot_3.png/revision/latest?cb=20160325110942",
      "source": "tora-dora.fandom.com"
    }
  ]
}
```
