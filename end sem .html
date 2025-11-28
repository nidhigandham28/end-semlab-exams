<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Simple Notes App</title>
<style>
    body {
        font-family: Arial, sans-serif;
        background: #f4f4f4;
        margin: 0;
        padding: 20px;
    }
    .container {
        width: 400px;
        margin: auto;
        background: white;
        padding: 20px;
        border-radius: 8px;
        box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    textarea {
        width: 100%;
        height: 80px;
        margin-bottom: 10px;
        padding: 10px;
        border-radius: 5px;
    }
    button {
        padding: 10px 15px;
        border: none;
        background: #28a745;
        color: white;
        border-radius: 5px;
        cursor: pointer;
    }
    button:hover {
        background: #218838;
    }
    .note {
        background: #fff8c4;
        padding: 10px;
        border-radius: 5px;
        margin: 10px 0;
        position: relative;
    }
    .actions {
        margin-top: 10px;
    }
    .actions button {
        background: #007bff;
        margin-right: 5px;
    }
    .delete-btn {
        background: #dc3545 !important;
    }
</style>
</head>

<body>
<div class="container">
    <h2>Notes App</h2>
    <textarea id="noteInput" placeholder="Write your note..."></textarea>
    <button onclick="addNote()">Add Note</button>

    <h3>Your Notes:</h3>
    <div id="notesList"></div>
</div>

<script>
    // Load notes from LocalStorage when page opens
    window.onload = loadNotes;

    function loadNotes() {
        let savedNotes = JSON.parse(localStorage.getItem("notes"))  [];
        document.getElementById("notesList").innerHTML = "";

        savedNotes.forEach((note, index) => {
            displayNote(note, index);
        });
    }

    function addNote() {
        let noteText = document.getElementById("noteInput").value;
        if (noteText.trim() === "") {
            alert("Please write something!");
            return;
        }

        let notes = JSON.parse(localStorage.getItem("notes"))  [];
        notes.push(noteText);
        localStorage.setItem("notes", JSON.stringify(notes));

        document.getElementById("noteInput").value = "";
        loadNotes();
    }

    function deleteNote(index) {
        let notes = JSON.parse(localStorage.getItem("notes"));
        notes.splice(index, 1);
        localStorage.setItem("notes", JSON.stringify(notes));
        loadNotes();
    }

    function editNote(index) {
        let notes = JSON.parse(localStorage.getItem("notes"));
        let updatedText = prompt("Edit your note:", notes[index]);

        if (updatedText !== null) {
            notes[index] = updatedText;
            localStorage.setItem("notes", JSON.stringify(notes));
            loadNotes();
        }
    }

    function displayNote(note, index) {
        const notesList = document.getElementById("notesList");

        notesList.innerHTML += `
            <div class="note">
                ${note}
                <div class="actions">
                    <button onclick="editNote(${index})">Edit</button>
                    <button class="delete-btn" onclick="deleteNote(${index})">Delete</button>
                </div>
            </div>
        `;
    }
</script>

</body>
</html>
