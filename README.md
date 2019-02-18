## Prerequisites

### API Key
@@ -20,14 +14,18 @@ The only module needed that is not in the standard library is the `requests` mod

In order to run, the script needs country codes for the countries to collect trending videos from. These are 2 letter country abbreviations according to ISO 3166-1. A list of all existing ones can be found [here](https://en.wikipedia.org/wiki/ISO_3166-1#Current_codes), however not all of these are assured to work with the YouTube API. This project comes with a list of 10 inside the `country_codes.txt` file.

### Video_ID

In order to run, the comment script needs video IDs updated in this "video_id.txt" file. Maximum 100 ids because of API limit. 

### Output Folder

In order to run, create an output folder in this root path.  

## Running the Script

The script is fairly simple to run, it takes the following optional parameters:

* `--key_path` which takes a path argument that targets the text file containing your API key. By default this is `api_key.txt` in the current directory.
* `--country_code_path` which takes a path argument that targets the text file containing the list of country codes to target. By default this is `country_codes.txt` in the current directory.
* `--output_dir` which takes a path argument that specifies the folder to create the output CSV files for each country. By default this is `output/` in the current directory.
