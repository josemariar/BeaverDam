Welcome to our Video Mapping Tool.

Your task is to accurately draw rectangles around different objects in each video. We need this so that we can train a computer to understand objects.

## Quick Instructions
1. Draw a box accurately around an object (covering every part you can see)
2. Hit 's' to go step through frames
3. Adjust the box to keep it accurate
4. Go back to the first frame and repeat for the next object
5. At the end, use the scene annotator to label the scenes.

## Example: Labeling people

### Detailed Instructions
1. We need you to draw an accurate box around each person you see in the video
2. We recommend you draw *one* person at a time from each video end to end and then rewind to the start for the next person
3. Best way to do this is frame by frame - hit 's' to move to the next frame and 'a' to move backwards 1 frame
4. You can skip frames when a person does not move. You will see a dotted line around that person.
4. If you don't see any people in the video for that frame then don't draw any rectangles
5. If the person disappears then delete the rectangle that represented that person (press 'd', or 'delete' with the box selected)

### Good:
![](https://raw.githubusercontent.com/wiki/xysense/BeaverDam/images/good_1.png)
![](https://raw.githubusercontent.com/wiki/xysense/BeaverDam/images/good_2.png)
### Bad:
![](https://raw.githubusercontent.com/wiki/xysense/BeaverDam/images/bad_1.png)
![](https://raw.githubusercontent.com/wiki/xysense/BeaverDam/images/bad_2.png)

### How accurate do you need to be?
We require a tight rectangle covering all of the person visible in that video frame.

## Keyboard Shortcuts

- `a` step back 1 frame
- `s` step forward 1 frame
- `space` play/pause
- `d` or 'delete' to delete selected rectangle

# Annotations

### How to add an annotation.

The annotations are the way to label the objects in the video. An annotation consists of a rectangle and labels.
An annotation can have multiple labels. The labels are selected through a checkbox.

![](https://github.com/josemariar/BeaverDam/blob/master/images/customlabels.png?raw=true)

Before drawing the rectangle, the user must check the correct labels. Otherwise, the annotation will have incorrect labels. The labels of an annotation can not be changed.

### How to add new labels

1. Go to /admin/ page
2. In the ANNOTATOR table, click on Add label
3. Write one name and select one color.
4. Save it

## Scene annotations

### How to add a scene annotation
1. Write the scene annotation name in the 'Scene Name' textbox
2. Click on 'Start scene' button
3. When the scene is finished, click on 'Finish scene' button

![](https://github.com/josemariar/BeaverDam/blob/master/images/scenesteps.png?raw=true)

## How to change the scene annotation visibility
Check (or uncheck) the 'Show Scene' checkbox

![](https://github.com/josemariar/BeaverDam/blob/master/images/showscene.png?raw=true)



