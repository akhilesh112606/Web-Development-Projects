# Web-Development-Projects - TOTAL (6)
## PROJECT - 1 : Movie Ranking Webpage (HTML)
## Algorithm

1. **Start** by creating an HTML document.
2. **Define** a `<h1>` header with the title "The Best Movies According to Akhil".
3. **Add** a `<h2>` subheader with the text "My top 3 movies of all-time." to introduce the list.
4. **Insert** a `<hr />` tag to create a horizontal line separator between the title and the movie entries.
5. **For each** movie in the list of top 3 movies:
   1. **Create** a `<h3>` header with the name of the movie.
   2. **Add** a `<p>` paragraph with a short description of why the movie is favored.
6. **End** the document.
<img width="731" alt="pic4" src="https://github.com/user-attachments/assets/ad1241a8-1c73-433c-8bbc-543d82535e98">

## PROJECT - 2 : Birthday Invitation Webpage (HTML)
## Algorithm
1. Start with the basic HTML structure containing headings, an image, and a list.
2. Identify the unordered list `(<ul>)`.
3. Replace the `<ul>` tag with an ordered list `(<ol>)`.
4. Keep each list item `(<li>)` the same.
5. Save and load the HTML to display numbered bullets instead of regular bullets.

<img width="716" alt="pic5" src="https://github.com/user-attachments/assets/0a67ca9a-1ebc-43ac-96c5-7cc729daab68">

##  PROJECT - 3 : Spanish Color Learner Webpage (HTML & CSS)
## Algorithm
1. Create an HTML file `(index.html)`.
2. Create a CSS file `(style.css)`.
3. Link the CSS file to the HTML file using `<link>` in the <head>.
4. In the CSS file, assign colors to each heading using their id.
5. Set all headings to have "font-weight: normal" using the .color-title class.
6. Set all images to be 200px in both height and width using the img selector.

<img width="272" alt="image" src="https://github.com/user-attachments/assets/0754ef86-2bae-4c24-bcb1-9303f6e990de">

##  PROJECT - 4 : Motivational Poster Webpage (HTML & CSS)
## Algorithm
1. Set up the HTML structure with a `<div>` containing the image and text.
2. Add CSS for styling the body, image, and headings.
3. Link Google Fonts for the Libre Baskerville font in the `<head>`.
4. Insert the image using the `<img>` tag.
5. Style the image with margin-left, margin-top, height, and a yellow border.
6. Set the color of the h1 heading to yellow and apply the Google font.
7. Style the h3 subheading with white color and the same font.
8. Set the body’s background color to black using CSS.
9. Ensure the external CSS file is linked in the <head> section.
10. Save and run the HTML file in a browser to display the styled content.

<img width="960" alt="pic4" src="https://github.com/user-attachments/assets/5c116fd0-8d2b-4c1d-8f3f-78227f825af1">

## PROJECT - 5 : Name Card Webpage (FLASK)
## Algorithm
1. **Initialize Flask Application**:
   - Import the `Flask` class from the Flask package.
   - Create an instance of the `Flask` application.

2. **Define Route**:
   - Set up the root URL route (`'/'`) with a function `greet()`.
   - Use the `render_template` function to return the `index.html` file when the route is accessed.

3. **Run Application**:
   - Use the `app.run(debug=True)` method to start the Flask server with debugging enabled if the script is run as the main program.

## PROJECT - 6 : Blog Website (FLASK)
## Algorithm
1. **Import Required Libraries:**
   - Import `Flask`, `render_template`, and `url_for` from the Flask framework.
   - Import the `requests` module for handling HTTP requests.

2. **Define Constants:**
   - Set `API_ENDPOINT` to the URL of the API that provides JSON data.

3. **Initialize Flask Application:**
   - Create an instance of the `Flask` class.

4. **Fetch Data from API:**
   - Use the `requests.get()` method to fetch data from the API endpoint.
   - Parse the JSON response and store it in `server_data`.

5. **Define Routes:**
   - **Root Route (`/`):**
     - Render the `index.html` template and pass `server_data` to it.
   - **About Route (`/about`):**
     - Render the `about.html` template.
   - **Contact Route (`/contact`):**
     - Render the `contact.html` template.
   - **Post Route (`/post/<int:index>`):**
     - Extract the post ID (`index`) from the URL.
     - Search for the post in `server_data` that matches the provided ID.
     - Render the `post.html` template and pass the matched post to it.

6. **Run the Application:**
   - Check if the script is run directly (i.e., `__name__ == "__main__"`).
   - Start the Flask development server by calling `app.run()`.



https://github.com/user-attachments/assets/4eb139bd-db16-4ee7-ad36-b48e9f6244d7



More projects will be added soon
