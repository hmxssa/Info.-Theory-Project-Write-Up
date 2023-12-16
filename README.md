<!DOCTYPE html>
<html>
  <head>
    <title>Info. Theory - Project Write Up</title>
  </head>
  
  <body bgcolor="#ddd" text="black" topmargin="0" leftmargin="0">
    <br><br>

      <center>
      <table border=0 width="850"> 
        <tr>
          <td colspan="3">
          <img src="star.png" width="850"/>
          
          <p> 
          &nbsp;&nbsp;&nbsp;<font size="+3" color="#643">Space Strike</font><br>
          <hr>
        </p>
          
        </td>
      </tr>
      <tr>
        <td valign="top" width="270">
        <font size="+2" color="#653"><b><i>Summary</i></b></font>
          <blockquote>
          A project to create a simple, yet addictive game based on old, nostalgic games we played when we 
          were once young. A 2d game with a player that avoids the falling of stars seeing how long they can 
          last with the time being counted.
          </blockquote><br>
        <font size="+1" color="#653"><b><i>Skills</i></b></font>
          <blockquote>
          ¬ Project Planning<br>
          ¬ Game Design<br>
          ¬ Info. Theory Incorporation<br>
          ¬ Creativity<br>
          </blockquote>
        </td>
        
        <td valign="top" colspan="2">
        
          <font size="+2" color="#653"><b><i>Scenario</i></b></font><br>
          <blockquote>
          My initial idea for this project was to create an encryption method, simply because I wanted
          it to meet all the project requirements in an intelligent way. As I began working on it, I realized
          that not only was it extremely unrealistic, but no progress was being made. I stressed more than I 
          was getting done. I was quite nervous to switch my project idea as I felt that it would make me 
          seem unintelligent and undetermined, which really I was only lost. Then I remembered how much more 
          my grade matters and everyone makes mistakes, so I ended up changing my idea. Best decision ever. 
          Not only does it meet the majority of the requirements, but I got so much more in one day with this 
          new idea than I did in 3+ days with the other idea. There were also so many websites and youtube videos
          that helped me both start, and get through this project. It was great and I learned so many new things!
          Now once I started my new idea, I wanted to do something from games or entertainment. My first thought 
          was to do a 3d game as it could be more fun and exciting to play. However, to make a fair balance of 
          design and coding could be challenging in a 3d game, and failing to do that, could be seen as lack 
          of knowledge and skill in the project product. As such, I chose to do a 2d game of a player avoiding to 
          clash with falling stars to avoid losing.
<br>
          </blockquote><br>

          <font size="+2" color="#653"><b><i>Overview</i></b></font><br>
          <blockquote>
         For my writing of my codes, I had to find a program that would support replit as I completed 
         my project there. The most reliable and known was pygame, so I used many of pygames functions
         and codes to write this game. There were many guides and helpful tips on their website and 
         other videos, so it wasn’t confusing for the most part. The hardest part would have to be getting 
         the values correct. For example, the size of the screen played a big part in having to run the
         code properly as not all screen sizes are the same. It could be extremely large on a mac, but 
         super small on a chrome book or such. Therefore I had to figure out how to make it fit either
         way, which was a part of my failing process as it was quite difficult to figure out. Another is 
         the actual loading of the background image. I wanted to follow a different procedure regarding
         the insertion of the picture because I had expected a different outcome, but nothing worked. I 
         even tried different functions but nothing was working. I then later realized that the only way 
         pygame will run its functions from replit is if the image is in the directory, and not just the file.
         It was quite a long process to figure, but once I did, it made my game testing so much easier and smoothly. 

        </td>
      </tr>
        <tr>
          <td>&nbsp;</td>
          <td valign="top">
          <font size="+2" color="#653"><b><i>Skill Descriptions</i></b></font><br>
          <blockquote>
          <font size="+1" color="#653"><b><i>Control Flow</i></b></font><br>
          <blockquote>
          Control Flow is visible everywhere in my project. Sequence, iteration, and conditional statements all 
          play a very crucial role in running my codes successfully. 
          Sequence - My code runs in an order from the top to bottom. It starts by the imports, making sure that 
          the program I’m using is in, the clock as it supports my time variable, and randomization. I also include 
          the variables I use throughout the code such as the height and width of the screen, player, star and even the velocity too.  
          Iteration - The while run loop is an example used for iteration in my game. This loop continues to run as long as
          the variable RUN is true. Inside this loop, there are for_in loops that re-goes three times to create 3 stars randomly 
          positioned in the sky. Actually, something quite interesting is that as the time being longer that a player lasts, more 
          stars start to fall and their speed increases as well. I think it’s actually quite good because it gets people to want to 
          practice even more to pass it. This is through the random import. 
          Conditional - Multiple functions such as if to check for key pieces being used and if one certain one is 
          pressed then a specific function will happen. This happens in the code “if keys [pygame.K_LEFT]. This is 
          also expressed in the if, else, and elif statements. They are used to execute a certain code among three actions that 
          a player may choose/perform. The draw function is also used a lot, as it’s responsible for the providing of the background, 
          player, stars, time, and game window. 
          The main function is what actually runs the majority such as the initial codes, the  loop of the game, the stars, player
          movement, collision of the two, and even the game over message. An addition is the delay and pressed functions. My game 
          pauses for 5000 milliseconds after the player loses, and the pressed indicates whether the left key or right key is getting 
          pressed. There are many additional factors and codes written in, but I only included those to make sure my code runs because of 
          the rules pygame offers. 
          Variables - The variables used are the WIN, player width, height, velocity, the stars width, height, and velocity,
          BASE_DIR, and the font used for display. All these variables allow for the working and loads of the player and objects in the game. 
</i>
            <br><br>
           The design is really what brings it all together. Beside is the picture I chose for my background in my game
          </blockquote>
          </td>
          <td valign="top"><br>
            <img src="img/stars.png" width="220">
          </td>
        </tr>
        <tr>
          <td>&nbsp;</td>
          <td colspan="2">

          <blockquote>
           The background I chose to do is obviously space themed, as there are stars falling 
           from the sky. I had a couple of options, but I didn’t want it to be too distracting. 
           There were many cool, unrealistic pictures available to use as the BG, but once I ran
           the code, the game was quite overshadowed by the background. I thought it was the color 
           of the background, so I tried keeping it more solid and bold, but with many designs.
           That still didn’t quite turn out the best, so I tried the opposite. I settled on the fact 
           that a colorful, abstract, and crazy background doesn’t suit my game background therefore 
           I chose a simple black background, white dots(stars), and a planet in the middle with rings
           (it may be Saturn but I don’t wish to assume). When I ran my code again, it looked so much 
           better and the game didn’t look messy or displeasing to view. Then it was time to figure out 
           the colors of the fonts and players. My initial plan was to keep everything white as it went 
           with the theme of space, but then I changed my idea to make it more diverse in those areas. 
           I wanted to switch it up a bit, while still making it look cute! Now the game doesn’t allow 
           players to choose the color of the player (I know, bummer), but they do get an amazing light
           pink rectangle! The pink color seemed so aesthetically pleasing to use, so I took the chance.
           I mean who doesn’t like pink?! I kept the time counter white since it was only a function and
           not something moving. The stars were originally going to be white, but I thought it was too basic 
           so I changed it to yellow. Then I wanted to also include asteroids but I felt like that would be
           too bland. Then again, I took in consideration of the background and noticed that there were 
           already stars, so I again changed it back to asteroids. I also feel like it’s more realistic in
           the sense of the real world. So yes it was quite a big change, but the outcome is better than the 
           stars. For the display of once a player loses, a “You Lost” text pops up in the center of the screen
           in blue. There was no motive behind it, I just felt that it was both cute and visible.
          <BR><BR>
            
          My codes and designs all tie together to make a simple, yet cute 2d game in which one can really test their 
          skills to get the best at. It uses information theory, such as iteration, selection, and sequence within 
          the pygame program, making the player steer and navigate to avoid falling rocks while having tracked the
          elapsed time. If one wants to play, please display your screen size to fit the size of the background image 
          for best results!

          <br><br>
            <img src="img/youlost.png" width="525" />
          
          </blockquote>
        
          <br>
        </td>
      </tr>
        <tr>
          <td colspan="3"><hr></td>
        </tr>
      </table>
      
    </center>
    
  </body>
</html>
