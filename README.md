# Ex.08 Design of Interactive Image Gallery
## Date:06/12/2025
## refno:25008479


## AIM:
To design a web application for an inteactive image gallery with minimum five images.

## DESIGN STEPS:

### Step 1:
Clone the github repository and create Django admin interface.

### Step 2:
Change settings.py file to allow request from all hosts.

### Step 3:
Use CSS for positioning and styling.

### Step 4:
Write JavaScript program for implementing interactivity.

### Step 5:
Validate the HTML and CSS code.

### Step 6:
Publish the website in the given URL.

## PROGRAM :
~~~
<div style="white-space: nowrap; overflow-x: auto; padding: 1rem;">
    <div style="display: inline-block; margin-right: 10px;" onclick="openModal(this)">
        <img src="c:\Users\Obsid_io\OneDrive\Pictures\Screenshots\Screenshot 2025-10-24 091048.png" style="height: 200px;">
    </div>
    <div style="display: inline-block; margin-right: 10px;" onclick="openModal(this)">
        <img src="c:\Users\Obsid_io\OneDrive\Pictures\Screenshots\Screenshot 2025-10-24 091107.png" style="height: 200px;">
    </div>
    <div style="display: inline-block; margin-right: 10px;" onclick="openModal(this)">
        <img src="c:\Users\Obsid_io\OneDrive\Pictures\Screenshots\Screenshot 2025-10-24 091308.png" style="height: 200px;">
    </div>
    <div style="display: inline-block;" onclick="openModal(this)">
        <img src="c:\Users\Obsid_io\OneDrive\Pictures\Screenshots\Screenshot 2025-10-24 091116.png" style="height: 200px;">
    </div>
    <div style="display: inline-block;" onclick="openModal(this)">
        <img src="c:\Users\Obsid_io\OneDrive\Pictures\Screenshots\Screenshot 2025-10-24 091334.png" style="height: 200px;">
    </div>
    <div style="display: inline-block;" onclick="openModal(this)">
        <img src="c:\Users\Obsid_io\OneDrive\Pictures\Screenshots\Screenshot 2025-10-24 091221.png" style="height: 200px;">
    </div>
    <div style="display: inline-block;" onclick="openModal(this)">
        <img src="c:\Users\Obsid_io\OneDrive\Pictures\Screenshots\Screenshot 2025-10-24 091324.png" style="height: 200px;">
    </div>
    <div style="display: inline-block;" onclick="openModal(this)">
        <img src="c:\Users\Obsid_io\OneDrive\Pictures\Screenshots\Screenshot 2025-10-24 091129.png" style="height: 200px;">
    </div>
</div>

<div id="modal" style="display: none; position: fixed; z-index: 1; left: 0; top: 0; width: 100%; height: 100%; background-color: rgba(0,0,0,0.9);">
    <span style="position: absolute; top: 15px; right: 35px; color: white; font-size: 40px; font-weight: bold; cursor: pointer;" onclick="closeModal()">&times;</span>
    <img id="modalImage" style="display: block; margin: 5% auto; max-width: 80%;">
</div>

<script>
    function openModal(element) {
        var modal = document.getElementById("modal");
        var modalImg = document.getElementById("modalImage");
        modal.style.display = "block";
        modalImg.src = element.querySelector("img").src;
    }

    function closeModal() {
        document.getElementById("modal").style.display = "none";
    }
</script>
~~~

## OUTPUT:
<img width="1919" height="962" alt="505072642-38038285-7c2a-47dc-a5d4-00183fec08ce" src="https://github.com/user-attachments/assets/3d873a82-cb9c-4649-960f-31ed70befa09" />
<img width="1902" height="902" alt="505072674-0c298e21-ff28-4a5d-8d3d-9f40c52fdc05" src="https://github.com/user-attachments/assets/6108bbc5-d813-4372-8b8c-577fefec51d1" />

## RESULT:
The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
