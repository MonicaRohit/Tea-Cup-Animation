# Tea-Cup-Animation
Tea Cup Animation using HTML and CSS is a simple and delightful animation that mimics the steam rising from a hot cup of tea. It is created using basic HTML markup and CSS properties.

To create this animation, you would start by setting up the HTML structure. You would need a container element, such as a <div>, to hold the tea cup image. 
Inside the container, you would place an image of a tea cup, which can be a <img> element.
  
Next, you would apply CSS styles to the container and the cup image. Set the container's position property to "relative" and give it a height and width that match the dimensions of the cup image.
Set the cup image's position to "absolute" and adjust its top and left properties to position it correctly within the container.

To create the vapour animation, you would utilize CSS keyframe animations. Define a new keyframe animation using the @keyframes rule. 
This animation will gradually change the opacity and position of the vapour element to give the illusion of steam rising.
  
Within the keyframes rule, specify different stages of the animation using percentages (e.g., 0%, 50%, 100%). At each stage, define the desired properties for the vapour element. 
For example, you can increase the opacity and adjust the top and left properties to create the rising effect.
  
Apply the animation to the vapour element by setting the animation property on it. Specify the animation name, duration, and timing function. 
You can also set the animation-iteration-count property to make the animation repeat.
  
Finally, to trigger the animation, you can use CSS animations. 
For example, you can add a class to the vapour element using JavaScript when the page loads, or you can use CSS animations to start the animation automatically.
