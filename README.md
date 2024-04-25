# Forward Coding Challenge: Build a Data Table Component with Form Integration

## Description:

Enhance the web application in this repository by incorporating a new page that fetches data from an API and presents the results in a data table component. Users should be able to append new data entries to the table via a form. The form should include input validation and provide users with informative messages for any erroneous inputs. Additionally, showcase your ability to style components using your favorite framework (e.g., Tailwind CSS).

## Requirements:

1. API Integration
   - Establish a connection to the MovieDB Org API to retrieve data (see details below)
1. Data Table Component:
   - Add a table component to the web page that displays the results from the API.
   - Populate the table with data representing various fields (e.g., title, description, vote_count, vote_average, release_date, popularity).
   - Add advanced features like ability to sort on a column and pagination
1. Form Integration:
   - Include a form on the web page for adding new data entries to the table.
   - The form should include input fields for each data field.
   - Implement validation for the form fields where needed
1. Styling Components:
   - Style the table, form, and input fields using your favorite CSS framework (e.g., Tailwind CSS).
   - Ensure that the components are visually appealing and consistent with the overall design of the web page.

## Resources

As a Database you can use any open API resource you feel most comfortable with.

Or this library: https://developer.themoviedb.org/reference/intro/authentication

api key=c33564c793ddb7f17ae433018aca11c3

access_token=eyJhbGciOiJIUzI1NiJ9.eyJhdWQiOiJjMzM1NjRjNzkzZGRiN2YxN2FlNDMzMDE4YWNhMTFjMyIsInN1YiI6IjY2MmJjMmM1OWFjNTM1MDExYzhmNWE0YSIsInNjb3BlcyI6WyJhcGlfcmVhZCJdLCJ2ZXJzaW9uIjoxfQ.jaOXctg8M48oY5Sf4VHs2p_2EG8ZXWle02RF-lx89B0

Example Usage:
GET https://api.themoviedb.org/3/movie/now_playing?page=2&api_key=c33564c793ddb7f17ae433018aca11c3 returns a list of movies you can display

Optionally, you can intercept each response to store movies in your local DB and add ability to add movie to the local DB

## Install the Forward Challenge App template

Follow these steps to set up the Forward Challenge App template on your local machine:

1. From the terminal, clone the repository

```console
$ git clone git@github.com:dbdventures/forward-challenge.git
```

2. Navigate to the cloned directory

```console
$ cd forward-challenge
```

3. Install dependencies

```console
$ pnpm i
```

4. Run the app

```console
$ pnpm dev
```

**Note:**
You have one hour to tackle this challenge. Complete as many of the requirements above as you can within the given time frame. Focus on showcasing your abilities and problem-solving skills. At the end of the hour, we'll review your solution together.

Good luck!
