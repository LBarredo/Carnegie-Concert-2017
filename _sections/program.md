---
title: Program
order: 2
published: true
---
Tentative Program 

- Ronen Shapira, Changing Reality #1: Spring
- Vivaldi, Spring
- Villa-Lobos, Bachianas Brasileiras No. 5
- Ronen Shapira, Changing Reality #2: Rhapsody in Blue
- Gershwin, Rhapsody in Blue
- Ronen Shapira, Changing Reality #3, Love and Despair

 _Intermission_

- Ronen Shapira, Changing Reality #4: Johan Sebastian
- PDQ Bach, Blaues Gras Cantata
- Yotam Ben Or, The young generation
- Ronen Shapira, Changing Reality #5: Strings of Peace


Program Notes

The first half of the concert will include two mixes on the theme of Changing Reality, adjacent to the two canonical pieces they echo. Vivaldi’s Spring, that represents the love of Nature and its protection, highlights our concern over climate change, while Gershwin’s Rhapsody in Blue, that recalls the challenges faced by immigrants and displaced people worldwide, represents concerns for social inclusion. The Bachianas Brazileras No. 5 by Heitor Villa-Lobos, which features the voices of lost tribes in the Amazon jungle, will be played in an arrangement made by the protégé of Villa-Lobos, Alfred Heller. This version is written for soprano, piano, and cello, and will be accompanied by video art about the Amazon and its people. The third part of Changing Reality, called “Love and Despair,” will engage most of the musicians participating in the concert in
a wild Bolero, a kind of prayer that surges as the piece progresses.

The second half opens with the Changing Reality mix “Johan Sebastian”, that introduces PDQ Bach’s Blaues Gras Cantata. PDQ Bach is a fictitious composer invented by musical satirist "Professor" Peter Schickele. NY-based Schickele developed a five-decade-long career, performing the "discovered" works of the "only forgotten son" of the Bach family. Schickele's music combines parodies of musicological scholarship, the conventions of Baroque and classical music, and
slapstick. Blaues Gras Cantata tells the story of a stranded “Georgian cracker” that
arrives in unfamiliar Kentucky to meet his “fairy Kentucky colonel”. The staged
dialogue between the two is hilarious, not only because it consists of Appalachian
slang translated to German (subtitles will be projected), but also because it is sung in an impossible mixture of Bach cantata style and bluegrass music, which only Schickele can produce. Of courses, this piece resonates Schickele’s family’s changing reality as German immigrants, as well as that of the Georgian cracker, who, disillusioned with Kentucky, returns to his home in
Savannah.

One twist of this wild piece is that it uses a harmonica instead of an organ to accompany the
recitatives. The harmonica player, together with his New York-based Jazz quartet, will perform a short Jazz piece of his own composition. It will be a tribute to the young generation. 

The composition ending the concert will be the fifth and final part of Changing Reality, called Strings of Peace. This piece, composed for piano and oud by Ronen Shapira, will be played by a Palestinian oud player and an Israeli pianist, ending the concert with a message of peace. The piece consists of a moving dialogue between east and west, in which the piano is played at the beginning and the end of the piece directly on the strings, not via the keyboard. A dancer will join the piece in the middle and perform an original choreography accompanied by video art. At the end of the piece, while the piano strings and the oud are played softly, the dancer will escort to stage all the musicians-turned-dancers, for a memorable message of hope ending the concert.


[comment]: <> (Do NOT edit.)
{% assign program = site.program | sort: 'order' %}
<ul class="performers">
{% for session in program %}
  <li>
  <h3 class="performer-name">{{ session.title }}</h3>
  {% if session.artist %}
  <h4 class="performer-focus">{{ session.artist }}</h4>
  {% endif %}
  {{ session.content }}
  </li>
{% endfor %}
</ul>
