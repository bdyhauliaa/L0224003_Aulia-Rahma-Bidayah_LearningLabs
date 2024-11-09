// Navigasi sederhana
const links = document.querySelectorAll('nav ul li a');
const sections = document.querySelectorAll('main');

links.forEach(link => {
    link.addEventListener('click', (e) => {
        e.preventDefault();
        const target = e.target.getAttribute('href').substring(1);
        sections.forEach(section => {
            section.style.display = 'none';
        });
        document.getElementById(target).style.display = 'block';
    });
});

// Interaktivitas form feedback
document.addEventListener('DOMContentLoaded', function() {
    const feedbackForm = document.querySelector('form');
    feedbackForm.addEventListener('submit', function(event) {
        event.preventDefault();
        alert('Thank you for your feedback!');
        feedbackForm.reset();
    });
});
