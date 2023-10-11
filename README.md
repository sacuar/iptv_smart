# IPTV [![update](https://github.com/iptv-org/iptv/actions/workflows/update.yml/badge.svg)](https://github.com/iptv-org/iptv/actions/workflows/update.yml)
Collection of publicly available IPTV (Internet Protocol television) channels  and RADIO channel from all over the world.
## Table of contents
- 📺 [Playlists](#playlists)
- RADIO CHANNELS
- 🗓 [EPG](#Others)
- 🗄 [Database](#database)
- 👨‍💻 [API](#api)

## Playlists

There are several versions of playlists that differ in the way they are grouped.

### Main playlist

Playlist includes all known channels except adult channels.

```
https://iptv-org.github.io/iptv/index.m3u
```

And here is the full version:

```
https://iptv-org.github.io/iptv/index.nsfw.m3u
```

### Grouped by category

<details>
<summary>Expand</summary>
<br>

Playlist in which each channel has its _category_ as a group title:

```
https://iptv-org.github.io/iptv/index.category.m3u
```

Same thing, but split up into separate files:

<!-- prettier-ignore -->
<table>
  <thead>
    <tr><th align="left">Category</th><th align="left">Channels</th><th align="left">Playlist</th></tr>
  </thead>
  <tbody>
    <tr><td>Animation</td><td align="right">53</td><td nowrap><code>https://iptv-org.github.io/iptv/categories/animation.m3u</code></td></tr>
    <tr><td>Documentary</td><td align="right">66</td><td nowrap><code>https://iptv-org.github.io/iptv/categories/documentary.m3u</code></td></tr>
    <tr><td>Education</td><td align="right">117</td><td nowrap><code>https://iptv-org.github.io/iptv/categories/education.m3u</code></td></tr>
    <tr><td>Entertainment</td><td align="right">353</td><td nowrap><code>https://iptv-org.github.io/iptv/categories/entertainment.m3u</code></td></tr>
    <tr><td>Family</td><td align="right">40</td><td nowrap><code>https://iptv-org.github.io/iptv/categories/family.m3u</code></td></tr>
    <tr><td>General</td><td align="right">1150</td><td nowrap><code>https://iptv-org.github.io/iptv/categories/general.m3u</code></td></tr>
    <tr><td>Kids</td><td align="right">186</td><td nowrap><code>https://iptv-org.github.io/iptv/categories/kids.m3u</code></td></tr>
    <tr><td>Lifestyle</td><td align="right">81</td><td nowrap><code>https://iptv-org.github.io/iptv/categories/lifestyle.m3u</code></td></tr>
    <tr><td>Movies</td><td align="right">279</td><td nowrap><code>https://iptv-org.github.io/iptv/categories/movies.m3u</code></td></tr>
    <tr><td>Music</td><td align="right">481</td><td nowrap><code>https://iptv-org.github.io/iptv/categories/music.m3u</code></td></tr>
    <tr><td>News</td><td align="right">707</td><td nowrap><code>https://iptv-org.github.io/iptv/categories/news.m3u</code></td></tr>
    <tr><td>Science</td><td align="right">26</td><td nowrap><code>https://iptv-org.github.io/iptv/categories/science.m3u</code></td></tr>
    <tr><td>Series</td><td align="right">161</td><td nowrap><code>https://iptv-org.github.io/iptv/categories/series.m3u</code></td></tr>
    <tr><td>Sports</td><td align="right">207</td><td nowrap><code>https://iptv-org.github.io/iptv/categories/sports.m3u</code></td></tr>
    <tr><td>Weather</td><td align="right">13</td><td nowrap><code>https://iptv-org.github.io/iptv/categories/weather.m3u</code></td></tr>
    <tr><td>XXX</td><td align="right">48</td><td nowrap><code>https://iptv-org.github.io/iptv/categories/xxx.m3u</code></td></tr>
  </tbody>
</table>

</details>

### Grouped by language

<details>
<summary>Expand</summary>
<br>

Playlist in which each channel has its _language_ as a group title:

```
https://iptv-org.github.io/iptv/index.language.m3u
```

Same thing, but split up into separate files:

<!-- prettier-ignore -->
<table>
  <thead>
    <tr><th align="left">Language</th><th align="left">Channels</th><th align="left">Playlist</th></tr>
  </thead>
  <tbody>
    <tr><td align="left">Arabic</td><td align="right">378</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/languages/ara.m3u</code></td></tr>
    <tr><td align="left">Bengali</td><td align="right">75</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/languages/ben.m3u</code></td></tr>
    <tr><td align="left">English</td><td align="right">2186</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/languages/eng.m3u</code></td></tr>
    <tr><td align="left">German</td><td align="right">275</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/languages/deu.m3u</code></td></tr>
    <tr><td align="left">Hindi</td><td align="right">162</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/languages/hin.m3u</code></td></tr>
    <tr><td align="left">Turkish</td><td align="right">216</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/languages/tur.m3u</code></td></tr>
    <tr><td align="left">Urdu</td><td align="right">59</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/languages/urd.m3u</code></td></tr>
  </tbody>
</table>

</details>

### Grouped by country

<details>
<summary>Expand</summary>
<br>

Playlist in which each channel has its _country_ as a group title:

```
https://iptv-org.github.io/iptv/index.country.m3u
```

Same thing, but split up into separate files:

<!-- prettier-ignore -->
<table>
  <thead>
    <tr><th align="left">Country</th><th align="left">Channels</th><th align="left">Playlist</th></tr>
  </thead>
  <tbody>
    <tr><td>🇧🇩 Bangladesh</td><td align="right">54</td><td nowrap><code>https://iptv-org.github.io/iptv/countries/bd.m3u</code></td></tr>
    <tr><td>🇩🇪 Germany</td><td align="right">267</td><td nowrap><code>https://iptv-org.github.io/iptv/countries/de.m3u</code></td></tr>
    <tr><td>🇮🇳 India</td><td align="right">438</td><td nowrap><code>https://iptv-org.github.io/iptv/countries/in.m3u</code></td></tr>
  </tbody>
</table>

</details>

### Grouped by region

<details>
<summary>Expand</summary>
<br>

Playlist in which each channel has its _region_ as a group title:

```
https://iptv-org.github.io/iptv/index.region.m3u
```

Same thing, but split up into separate files:

<!-- prettier-ignore -->
<table>
  <thead>
    <tr><th align="left">Region</th><th align="left">Channels</th><th align="left">Playlist</th></tr>
  </thead>
  <tbody>
    <tr><td align="left">Arab world</td><td align="right">418</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/regions/arab.m3u</code></td></tr>
    <tr><td align="left">Asia</td><td align="right">2949</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/regions/asia.m3u</code></td></tr>
    <tr><td align="left">Asia-Pacific</td><td align="right">1939</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/regions/apac.m3u</code></td></tr>
    <tr><td align="left">Central and Eastern Europe</td><td align="right">1055</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/regions/cee.m3u</code></td></tr>
    <tr><td align="left">Central Asia</td><td align="right">63</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/regions/cas.m3u</code></td></tr>
    <tr><td align="left">South Asia</td><td align="right">593</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/regions/sas.m3u</code></td></tr>
    <tr><td align="left">Southeast Asia</td><td align="right">497</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/regions/sea.m3u</code></td></tr>
    <tr><td align="left">Western Europe</td><td align="right">1011</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/regions/wer.m3u</code></td></tr>
  </tbody>
</table>

</details>
### Radio Channels
<details>
<summary>Expand</summary>
<br>
Radio Foorti
```
http://119.148.23.88:1021/
```
</details>
## Others
<details>
<summary>Expand</summary>
<br>

## EPG

[Electronic Program Guide](https://en.wikipedia.org/wiki/Electronic_program_guide) for most of the channels can be downloaded using utilities published in the [iptv-org/epg](https://github.com/iptv-org/epg) repository.

## Database

All channel data is taken from the [iptv-org/database](https://github.com/iptv-org/database) repository. If you find any errors please open a new [issue](https://github.com/iptv-org/database/issues) there.

## API

The API documentation can be found in the [iptv-org/api](https://github.com/iptv-org/api) repository.

## Resources

Links to other useful IPTV-related resources can be found in the [iptv-org/awesome-iptv](https://github.com/iptv-org/awesome-iptv) repository.

</details>






