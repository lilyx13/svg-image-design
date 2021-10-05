# README

## Compound Shape
[Android Logo](https://i0.wp.com/www.techweez.com/wp-content/uploads/2013/10/Android-logo.jpg?fit=1024%2C768)

### Steps
1. Create the body
  - Create a rectangle
  - add curve to the corners
  - create another rectangle
  - use the second rectangle to clip the first so it has a sharp edge
2. Create the head
  - Create an ellipse (probably not a circle)
  - cut the ellipse in half
  - create 2 small ellipses
    - position them in the head
    - use them to subtract from the head
  - create 2 small lines for antenna
    - curve the ends
    - union them to the head in position
  - align the head to the body
3. Add the Limbs
  - Create a rectangle
  - Add a heavier curve to the ends
  - duplicate to make 4 versions
  - position 2 against the body for arms
  - position 2 under the body, half way covered by the body
  - use the align tool to make sure everything looks good
  - union the limbs together
  - union the limbs to the body
4. Ready to Deploy


## Star Logo
- This demo is based off of [this logosbynicktutorial](https://www.youtube.com/watch?v=3xjXd5EPcsQ&t=346s)

### Techniques
- Create ellipse, star, and line
- Subtract from a path using another path
- Align text to a path
- Duplicate items

### Steps

1. Create lines
  - create a line
  - clip it in 2 places
  - remove the 2 clips
  - union the remaining piece
  - make another line
  - duplicate them both in circles and then union them
  - intersect the two shapes and offset them
2. create a star
  - Create 2 starts
  - make one of them a bit bigger than the other
    - then give it 2point curve
  - use the larger one to subtract from the center of the circle
  - place the smaller star with 1point curve into the space
3. Create Banner
  - Create an ellipse
    - only use the stroke
      - remove the fill
    - set the stroke to be fairly wide
  - create a rectangle
  - cut the circle in half with the rectangle
  - create two triangles
    - use the triangles to clip out the ends of the banners
  - position the banner under the star and line shape
4. Add Text
  - Write text and choose a typeface
  - use the arc plugin with it selected
  - guestimate a good arc
  - position the text over the shape
5. Group the items together

### Plugin
- Arc for making text on a circle
