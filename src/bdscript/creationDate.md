# $creationDate
Returns the creation date of any valid Discord Snowflake ID.

## Syntax
```
$creationDate[ID;(Format)]
```

### Parameters
- `ID`: The ID from which to get the creation date.
- `Format`: Customize the default time format output (Optional).

   > 📌 Click [me](../resources/timeFormat.md) to check all supported time format values.

## Example
- Default format
   ```
   $nomention
   $creationDate[$authorID]
   ```

   ![example](https://user-images.githubusercontent.com/69215413/127032089-ef8aa439-89c9-46b2-a2e4-cdf54ab7fa6b.png)
- Custom format
   ```
   $nomention
   $creationDate[$authorID;January 2, 2006 at 3:04 PM (MST -07:00)]
   ```

   ![example](https://user-images.githubusercontent.com/95774950/197385800-92a434d2-e388-4067-8a78-d9357f6184bd.png)
