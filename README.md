# WildeCard Project

Welcome to the WildeCard project! This fun application is designed to help you decide what to do when you're bored. Instead of going wild, let's get Wilde!

## How It Works

The application is divided into four main categories: Sports, Movies, Video Games, and Music. Each category offers a set of options, and you can choose based on your interests. The program will then provide a suggestion from the chosen category.

## Sports

In the sports category, you can choose your favorite sport and region. The application will then randomly suggest a team for you to watch. Here's a snippet of the sports data:

```python
# Sample Sports Data
option1dict = {
    'Boston Celtics': ("Basketball", "Northeast"),
    'Brooklyn Nets': ("Basketball", "Northeast"),
    # ... (other teams)
    'Vancouver Whitecaps FC': ("Soccer", "Northeast")
}
```

## Movies

For movies, you can choose the genre and age group. The application will then recommend a movie for you to watch. Here's an example of the movies data:

```python
# Sample Movies Data
option2dict = {
    'Coco': ("Action", "0-12"),
    'Zootopia': ("Action", "0-12"),
    # ... (other movies)
    'The Edge Of Seventeen': ("Comedy", "13-18")
}
```

## Video Games

In the video games category, you can select the genre and gaming console. The program will then suggest a video game for you. Here's a snippet of the video games data:

```python
# Sample Video Games Data
option3dict = {
    'Astro’s Playroom': ("Playstation", "Puzzle"),
    'Deathloop': ("Playstation", "Shooter"),
    # ... (other games)
    'ARMS': ("Nintendo Switch", "RPG")
}
```

## Music

Finally, in the music category, you can choose the genre and age group. The application will recommend a song for you to listen to. Here's a snippet of the music data:

```python
# Sample Music Data
option4dict = {
    'Take Five by Dave Brubeck': ("Jazz", "0-12"),
    'So What by Miles Davis': ("Jazz", "13-18"),
    # ... (other songs)
    'Charity Ball by Fanny': ("Rock", "25+")
}
```

## How to Use

1. Run the program.
2. Choose a category based on your interests.
3. Follow the prompts to make more specific selections.
4. Get your WildeCard suggestion!
5. Have fun and enjoy your suggested activity.

## Dependencies

This project relies on the following:

- **DictsForCompSciProject Module**: Imported module containing dictionaries used for data processing.
- **WildeCard Module**: Contains functionality for Wilde Card application.
- **Tkinter**: Python's standard GUI toolkit.
- **unittest**: Python's built-in unit testing framework used for testing purposes.


Feel free to customize the code and add more options to make it even more entertaining! If you have any questions or suggestions, feel free to reach out!
