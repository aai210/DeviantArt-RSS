# DeviantArt RSS

Most DeviantArt features are available through RSS feed. For how to create RSS in DeviantArt, you can read the official instructions for example in ["How do I use RSS Feeds?"](https://www.deviantartsupport.com/en/article/how-do-i-use-rss-feeds) or "[Access deviations with RSS feeds"](https://www.deviantart.com/developers/rss). But even so, I managed to run into problem of creating RSS Feeds.

**I found two solutions for how to form a tape:**

#### 1. We use an example from DeviantArt with changes.

```https://backend.deviantart.com/rss.xml?type=deviation&q=[name]+sort%3Atime+meta%3Aall```

For example https://backend.deviantart.com/rss.xml?type=deviation&q=zeon-in-a-tree+sort%3Atime+meta%3Aall

This method does not work with all profiles and for some profiles this method does not work.

#### 2. This is a universal way to create RSS Feeds.

```https://backend.deviantart.com/rss.xml?q=gallery:[name]```

For example https://backend.deviantart.com/rss.xml?q=gallery:zeon-in-a-tree

Also in this [repository](https://github.com/jamesl1001/deviantART-API) I found how to access a specific gallery

For example ```https://backend.deviantart.com/rss.xml?q=gallery:[deviant name]/[gallery]```


