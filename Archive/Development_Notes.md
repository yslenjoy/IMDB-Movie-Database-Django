## Development Notes
### Next Stage Work (after first demo 03/26/2019)
- [x] Add more information about other entity: Actors, Directors
- [-] Another information for Movies entity:
	- [-] Using IMDB movie ID (e.g 0499549) in Movie data
	  **This time manually-created ID is used (from 1 to 1100)**
	- [x] Link
	- [-] poster (for better visulization)
- [-] Add more information about movie: create seperate table for prize:
	* Prize(movieID, prize)
	* Movie_Genre(movieID, Genre_1, Genre_2, Genre_3) 
	* .... (to be added)
Same for Actors, Directors
- [x] Prediction and recommendation
- [x] Better UI
- [-] More search types with dropdown box
- [x] Pagination

(If time allows)
- [ ] Localhost to domain name (using Cpanel): Extract credit

### Misc Notes
* Useful Python packages:
	+ [sqlite3](https://docs.python.org/2/library/sqlite3.html): python sqlite connection
	+ [imdbpie](https://pypi.org/project/imdbpie/): IMDB data
* Possible sofrware to open .sqlite: [sqlitebrowser](https://sqlitebrowser.org/blog/version-3-11-1-released/)
* Similar Projects:
	+ [Media-Hub](https://github.com/JeeveshN/Media-Hub)
	+ [NBA DB](https://www.youtube.com/watch?v=KvlmgWRDzqo&t=9s)
	+ [Moviehunter](https://github.com/BruceHenry/movie-website-django)
* <del> Add data into `db.sqlite3`:
    `python3 add_data.py`</del>
* Superuser: group50, yslenjoy@gmail.com, 411group50

### Potential improvements
- [-] Web scraping files are not elegant (much data preprocessing is still need for the crawled data)
- [ ] Website deployment
- [ ] Add user login system
