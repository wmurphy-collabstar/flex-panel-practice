# Flex Panel Project
> This project is an extension of the Flex Panel exercise from [WesBos's Javascript30 Course](https://github.com/wesbos/JavaScript30), where the goal is to make a response photo gallery consisting of panels that can be opened to include a full inspirational quote when clicked. It helped me practice Flexbox, CSS transitions, and inserting dynamic content with Javascript using event listeners. I added my own twist by adding changed design when each panel is hovered over or focused on, and added another row of panels to make a grid design.

## Features
- Two rows of interactive panels that animates a quote or pun when opened, and shows the main word of the panel only when closed
- A Photo Credits page to acknowledge where the gallery photos come from
- A nav bar connecting the Home page and Photo Credits page together 
- A Shuffle button that reorders the panels randomly to create new fun phrases horizontally and vertically

## Design
For each panel, when it is in its normal state, I wanted the hover effect to pop, so I desaturated and blurred the panels when not actively hovered over, and removed those filters when the panel is hovered over. It gives the illusion that the image is brighter than normal, when really that is the normal saturation. I also increased the transparency of the background color behind the text so the image is the focal point of the panel.

I wanted to make the panels accessible as well, so I added a `tabindex` attribute to each panel so the user can see the same design transitions navigating through the panels with the keyboard. 

When the panels are opened (via mouse or keyboard), I decided to keep the same theme of styling consistent. I removed the `saturation` and `blur` filters, but instead decided to make the background color behind the text more transparent _only_ when the element is hovered or focused on. That way the images are hiding when panels are untouched and it can lead the user to want to hover over each panel to see the image underneath. 

## Running the project
### Live version
[Flex Panel Gallery](#)

### From the repo
1. Clone this repo locally
2. Copy the path to the HTML file
3. Paste the path into the browser address bar
4. Press enter

### Prerequisites

The things you need before installing the software.

* LTS version of Node installed
* A terminal
* A code editor if you plan on inspecting, editing, or contributing to the code.

### Installation

A step by step guide that will tell you how to get the development environment up and running.

```
$ git clone https://github.com/wmurphy-collabstar/flex-panel-practice.git
$ cd flex-panel-practice
$ code .
```
> **Note**: The last command works if you have it configured to open up your editor from the terminal (as you can with Visual Studio Code)

### Branches

* Main: The branch with the latest stable version of the website

