# tyler-pcsd.github.io

[tyler-pcsd.github.io](https://tyler-pcsd.github.io)

## How to Request More Activities

## How to Add More Activities

* Find an activity from this list under the **browser-based** section:
  * [List](https://github.com/leereilly/games#user-content-browser-based) (link)

<img width="1440" alt="Screen Shot 2021-09-28 at 12 11 27 PM" src="https://user-images.githubusercontent.com/87149999/135142270-7927f56a-4354-4d10-9606-17edc135f1cf.png">

* Download the zip file from its GitHub folder
<img width="729" alt="github-download" src="https://user-images.githubusercontent.com/87149999/135142043-c1917f48-210d-4c2d-a9e7-896cfa04b328.png">

* Drag the zipped file into the activities folder
* Unzip the zipped file
* Rename the folder to {activity}
* Change index.html (inside the new folder!) to {activity}.html (replace {activity} with the name of the activity)
* Double-click {activity}.html to make sure it still works
* Take a screenshot of the game title screen and save the image to the images folder

Copy this block of code:

<!-- card for activity and description -->
            <div class="card" style="width: 18rem;">
                <img class="card-img-top" src="/images/{image}.png" alt="{image description}">
                <div class="card-body">
                    <h5 class="card-title">{title}</h5>
                    <p class="card-text">{description}
                    </p>
                    <a href="/activities/{activity}/{activity-index}.html" class="btn btn-primary">Play</a>
                </div>
            </div>
            
Change the values in { } in the code to match the new activity:

* {image}
* {image description}
* {title}
* {description}
* {activity}

And paste it 2 lines under the last similar code block
