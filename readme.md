PacktPub free ebooks downloader
===============================

The original is at : github.com:vladimyr/packtpub-downloader.git

This utility downloads free ebook offered daily from packtpub.com
publishing service.

## Installation

```bash    
npm install -g vladimyr/packtpub-downloader
```

## Configuration

PacktPub downloader uses JSON configuration for retrieving login 
credentials. Example of configuration:

```json
{
  "username": "<put your username here>",
  "password": "<put your password here>"
  "basedir": "<optional: books repo dir>"
}        
```


## How to use

Invoke inside your terminal with provided path to configuration file.
Optionally you can force specific download type or redirect download to
stdout for further redirections:

```bash
packtpub-download -c <path_to_config_file> [-t "pdf|epub|mobi" -o <use-stdout> -f "books_dir"]
```
