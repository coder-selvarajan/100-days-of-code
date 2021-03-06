# 100 Days Of Code - Log

### Day 1: Aug 7, Friday

**Today's Progress**: I have gone through some tutorials on Flutter - CustomPainter widget and experimenting basic shapes in Thayam project to build game-board

**Thoughts** I have been learning Flutter app development for sometime. Now I wanted to build a game app as part of #100daysofcode challenge. The game name is 'Thayam' it's a ludo type game based on South-India.

**Link(s) to work :** [Thayam App](https://github.com/coder-selvarajan/thayam_flutter)

### Day 2: Aug 8, Saturday

**Today's Progress**: Calculating positions and building game-board using custompainter widget.

**Thoughts** Went thru many tutorials about CustomPainter - The one from raywenderlich.com was really helpful in understanding custompainter better. The canvas size issue needs to be fixed.

**Link(s) to work :** [Thayam App](https://github.com/coder-selvarajan/thayam_flutter)

### Day 3: Aug 9, Sunday

**Today's Progress**: Built the game-board with all squares and crosses. Bit of refactoring.

**Thoughts** Happy that I was able to calculate all the positions and made up the game-board

**Link(s) to work :** [Thayam App](https://github.com/coder-selvarajan/thayam_flutter)

### Day 4: Aug 10, Monday

**Today's Progress**: Adding pawn stage circles and controlling canvas sizing

**Thoughts** Drawing cricles were easy as other squares... and I was trying to control the size of the canvas in many ways but could nt achieve it. However accidently I have changed the parent widget to Stack and the sizing started working automatically ;)

**Link(s) to work :** [Thayam App](https://github.com/coder-selvarajan/thayam_flutter)

### Day 5: Aug 11, Tuesday

**Today's Progress**: Trying to add Pawn images on the game-board via canvas.drawImage method.

**Thoughts** I am still struggling to paint the image on the canvas. I could not find any clear online solution on this topic.

**Link(s) to work :** [Thayam App](https://github.com/coder-selvarajan/thayam_flutter)

### Day 6: Aug 12, Wednesday

**Today's Progress**: Finally drawn the pawn images on the canvas. Did bit of image tweaks in AdobeXD.

**Thoughts** After hours of R&D with image draw finally found a solution which loads the image in async way in the main.dart file itself.

**Link(s) to work :** [Thayam App](https://github.com/coder-selvarajan/thayam_flutter)

### Day 7: Aug 13, Thursday

**Today's Progress**: Refactoring and adding separate pawn class for pawns and to add interactive events

**Thoughts** Need to keep pawn positions in an array and serve from main class. GestureDetector or InkWell to be used for adding tab events.

**Link(s) to work :** [Thayam App](https://github.com/coder-selvarajan/thayam_flutter)

### Day 8: Aug 14, Friday

**Today's Progress**: Refactoring color & position constants. Adding pawns via new Pawn class.

**Thoughts** Spend sometime learing Animations in Flutter. Need to check how to make image based animations.

**Link(s) to work :** [Thayam App](https://github.com/coder-selvarajan/thayam_flutter)

### Day 9: Aug 16, Sunday

**Today's Progress**: Trying out different approach for creating pawns - using image widgets with animation by AnimatedPositioned

**Thoughts** Need to learn about Animation in full swing. Currently i am unclear about various animation types & facilities

**Link(s) to work :** [Thayam App](https://github.com/coder-selvarajan/thayam_flutter)

### Day 10: Aug 17, Monday

**Today's Progress**: Going thru Flutter animation tutorials in flutter.dev and in Udemy course. Working out codelab and sample projects

**Thoughts** Still lot of concepts in animation to be covered.

### Day 11: Aug 18, Tuesday

**Today's Progress**: Another day with the Udemy course by Stephen Grider and working out his sample project.

**Thoughts** More to cover though.

### Day 12: Aug 20, Thursday

**Today's Progress**: Practiced udemy course project independently as a coding kata for practice in animation.

**Thoughts** I wish to do more coding katas in Flutter.

### Day 13: Aug 21, Friday

**Today's Progress**: Rearranged widgets and classes - Added pawn animation with AnimatedBuilder.

**Thoughts** Currently the board paint method is called everytime the animation progress. need to optimize it.

### Day 14: Aug 24, Monday

**Today's Progress**: Initializing player tracks array and playing around with pawn movements.

**Thoughts** Now there is an error in the track class. Pawn is not moving.

**Link(s) to work :** [Thayam App](https://github.com/coder-selvarajan/thayam_flutter)

### Day 15: Aug 27, Thursday

**Today's Progress**: Applying adaptive layout for the board - refactoring player track positions - optimizing animation logic a bit.

**Thoughts** So far all the animation logic is done for single pawn. I need to replicate the logic for all other pawns in optimistic approach.

**Link(s) to work :** [Thayam App](https://github.com/coder-selvarajan/thayam_flutter)

### Day 16: Aug 28, Friday

**Today's Progress**: Refactoring Pawn class and adding all the pawns and positioning them properly with appropriate tracks. Controlling the animation movements with random number within 6.

**Thoughts** Now that the basic board and pawn setup is ready with their movements. Next step is to manifest out the dice functionality.

**Link(s) to work :** [Thayam App](https://github.com/coder-selvarajan/thayam_flutter)

### Day 17: Aug 31, Monday

**Today's Progress**: Created player stages and adding dice to it with rolling facility. Also did a bit of refactoring work.

**Thoughts** Next I need to link the dice rolling with the pawn movement.

**Link(s) to work :** [Thayam App](https://github.com/coder-selvarajan/thayam_flutter)

### Day 18: Sep 1, Tuesday

**Today's Progress**: Moving pawns based on dice score for the player. Adding small circles to the mountains. 

**Thoughts** Need to list down all little animations required for the app. 

**Link(s) to work :** [Thayam App](https://github.com/coder-selvarajan/thayam_flutter)

### Day 19: Sep 2, Wednesday

**Today's Progress**: Experimenting text painting with custom painter with canvas rotation - Achieved the desired effect with simple RotatedBox widget.

**Thoughts** Next I need to concentrate on positioning of multiple pawns within single spot.

**Link(s) to work :** [Thayam App](https://github.com/coder-selvarajan/thayam_flutter)
