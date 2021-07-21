# SerenityOS User Map

A map showing where in the world the SerenityOS developers and users are :^)

**[Visit the map!](https://usermap.serenityos.org)**

## Contribution

If you want to add yourself to the map, make a PR that adds an entry to the file [`people.json`](./people.json). It has to have the following format:

```json
{
  "nick": "denvercoder9",
  "coordinates": [48.77844, 9.18014],
  "links": {
    "Website": "https://example.com",
    "GitHub": "https://github.com/denvercoder9"
  }
}
```

If you're a [contributor](https://github.com/SerenityOS/serenity/graphs/contributors), add `"contributor": true` at the end of the entry as well to get highlighted on the map.

Some tips:

- You can find your location with either [OpenStreetMap](https://www.openstreetmap.org/), [Google Maps](https://www.google.com/maps) or your mobile phone if GPS is enabled
- `links` is an object where each key will be displayed as a link with the string content as `href`.
- You decide how precise you want it to be. On your room, just the right street, the center of the city, center of the country. You decide!
