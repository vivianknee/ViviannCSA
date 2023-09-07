---
comments: true
layout: post
title: Pair Plan Feedback
description: Feedback from Chat GPT and Peers
courses: { csa: {week: 2} }
type: hacks
---

- Chat GPT feedback on code:
    - chat gpt noticed that its possible that when the code randomly chooses a color, repeat colors may occur so it wrote some code to ensure that each hex is unique.
    
<script>
    document.getElementById('generate-palette-button').addEventListener('click', () => {
    const colorInput = document.getElementById('color-input').value.toLowerCase();
    const colorPalette = colorPalettes[colorInput] || colorPalettes.default;

    // Shuffle the colorPalette array to randomize the colors
    const shuffledPalette = shuffleArray(colorPalette);

    // Apply the shuffled colors to the UI elements
    for (let i = 0; i < colors.length; i++) {
        colors[i].setHex(shuffledPalette[i % shuffledPalette.length]);
    }
    });

    // Function to shuffle an array
    function shuffleArray(array) {
        const newArray = [...array];
        for (let i = newArray.length - 1; i > 0; i--) {
            const j = Math.floor(Math.random() * (i + 1));
            [newArray[i], newArray[j]] = [newArray[j], newArray[i]];
        }
        return newArray;
    }
</script>

- Peer Feedback
