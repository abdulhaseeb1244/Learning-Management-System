document.addEventListener('DOMContentLoaded', () => {
    const themeToggleButton = document.getElementById('theme-toggle');
    const body = document.body;
  
    // Toggle theme
    themeToggleButton.addEventListener('click', () => {
      body.classList.toggle('dark');
      const isDarkMode = body.classList.contains('dark');
      themeToggleButton.textContent = isDarkMode ? 'Dark Mode' : 'Light Mode';
    });
  });
  