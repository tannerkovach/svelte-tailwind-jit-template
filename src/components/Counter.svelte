<script>
    let count = 0;
    let plusOne = function() {
        count++;
    }
</script>

<button class="border border-gray-500 rounded-md hover:bg-gray-300 px-4 py-1" on:click="{plusOne}">Count - {count} </button>