# TheMovieDB.Custom
This agent is based on the original **TheMovieDB** plugin.

The main difference from the original version:
- Added the ability to search using the ID from TV show (e.g. tmdb1750)
- Added the ability to match it towards an episodes group from TMDB

*The movie search for this agent is currently untested.*

## Examples
[Naruto](https://www.themoviedb.org/tv/31910-naruto-shipp-den) tmdb-ID = 31910

This will give you three results currently when you *manually* search/match in Plex.

Supported search queries:
`tmdb31910`
`tmdb 31910`

- Naruto Shippūden
- Naruto Shippūden - Released Order Episodes
- Naruto Shippūden - Correct order

You can then select the one you want to match it with and Plex will fetch the metadata accordingly.


## Install
1. If you want to install the agent manually or if you are interested in the source code, you can download the latest copy of the agent
2. Move TheMovieDB.Custom.bundle to the default plugins folder. [FAQ](https://support.plex.tv/articles/202915258-where-is-the-plex-media-server-data-directory-located/)            
   `%LOCALAPPDATA%\Plex Media Server\Plug-ins` for Windows Vista/7/8/10
   