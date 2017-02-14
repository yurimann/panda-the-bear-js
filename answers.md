var image = $('.profile-image')
$(image[0]).attr('src', 'https://placebear.com/400/400');

$('h1.highlight').text("Yuri the Bear");

var icon = $('#employment h3.info-title i.icon-suitcase')
$('#employment h3.info-title').text("    My Jobs!").prepend(icon)

$('.bar-default')[2].remove();

$('body').css('background', 'darksalmon');

$('.highlight').css('color', 'blue');

$('h1').css('font-family', 'monospace');

$('.action-icon-bg').css('background-color', 'black');

$('#name').attr('placeholder','Identify yourself')

$('#message').attr('placeholder', 'State your business!');

$('#name').attr('value','Your Nemisis')

$('#email').attr('value','koalathebear@gmail.com')

$('#submit').attr('value', 'En garde!');

$('#submit').attr('disabled', 'disabled');

('li.bio-info-item').empty();

$('[title="Pikachu"]').clone().insertAfter('form')

for (i=0; i < 10; i++) {$('#right-image img').clone().insertAfter('section');}

date = new Date();
leftSpanData = document.createElement('span');
leftSpanData.append(date);
listItem.append(leftSpanData);
$('ul.bio-info').append(listItem);
