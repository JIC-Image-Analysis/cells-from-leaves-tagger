# Image tagging

This annotation tool is used to post process data generated using the
[cells-from-leaves](https://github.com/JIC-Image-Analysis/cells-from-leaves)
image analysis.

## Key bindings

| Action         | Key   |
| -------------- | ----- |
| Open directory | ``o`` |
| Tag as "good"  | ``1`` |
| Tag as "bad"   | ``2`` |
| Next image     | ``RightArrow``, ``l`` |
| Previous image | ``LeftArrow``, ``h`` |
| Fast forward   | ``f`` |
| Rewind         | ``r`` |
| Toggle help    | ``h`` |
| Save           | ``s`` |
| Quit           | ``Esc``, ``q`` |

## To install

* Install node.js and npm
* Run ``npm install``

## To run

* Run ``npm start``
* *Warning:* ``sudo npm start`` is required if the initial processing was done using Docker
