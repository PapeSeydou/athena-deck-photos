# ATHENA deck photos

Photo research for a private sales deck for ATHENA, a school management platform used in Senegal and West Africa.

34 photographs, every one of a real school, taken by a real photographer. No AI images, no watermarks, no
renders. Each file is at least 2400 px on its long edge and under 8 MB. The people are Black African
students, teachers, parents and administrators. Students run from preschool to high school, and there are no
university or college students in the set.

## Layout

    photos/<SLOT>/<SLOT>_<n>.jpg    the images, one folder per deck slot
    contact-sheets/<SLOT>.jpg       thumbnails with filenames, one per slot
    contact-sheets/ALL.jpg          overview of every photo in the set
    sources.csv                     filename, slot, source URL, photographer, width, height

## Slots and top picks

| Slot | What it is for | Count | Top pick |
|---|---|---|---|
| HERO-COVER | Opening slide. A student concentrating over a notebook, landscape, subject right of centre, calm background on the left where the title sits. | 3 | HERO-COVER_1 |
| CUTOUT-PORTRAITS | Four head and shoulder portraits on plain backdrops, one per age band plus a backpack shot, for cutting out into avatars or testimonial faces. | 4 | CUTOUT-PORTRAITS_2 |
| GROUP-CLASS | The classroom as ATHENA runs it: a teacher leading a full class, students raising hands, students working in small groups. | 3 | GROUP-CLASS_2 |
| GROUP-YARD | Schoolyard energy, arrival and play. | 2 | GROUP-YARD_2 |
| GROUP-HIGHSCHOOL | Teenagers studying together, for the secondary-school chapter. | 2 | GROUP-HIGHSCHOOL_1 |
| SUCCESS | Achievement: end of year ceremony, certificates, graduation. | 2 | SUCCESS_2 |
| TEACHER | One teacher's day: at the board, entering marks on a laptop, helping one student. | 3 | TEACHER_1 |
| SCHOOL-ADMIN | The director or administrator at work, professional dress, desk or office. | 2 | SCHOOL-ADMIN_2 |
| PARENT | The parent side of the product: phone at home, and the school run. | 3 | PARENT_3 |
| BOARDING | Dormitory life and evening study, for boarding schools. | 3 | BOARDING_3 |
| SCHOOL-BUILDINGS | Exteriors for the multi-site story, including one aerial. | 3 | SCHOOL-BUILDINGS_3 |
| ADMIN-WORKLOAD | The paper mountain the platform replaces: registers, files, folders. | 1 | ADMIN-WORKLOAD_1 |
| SCHOOL-BUS | Children riding or boarding a school bus. | 2 | SCHOOL-BUS_1 |
| CANTEEN | Students eating together at school. | 1 | CANTEEN_1 |

## Why these picks

HERO-COVER_1 puts a uniformed student over her notebook on the right of the frame with warm, quiet space to
her left. It is the only hero shot in the set that was taken by a Senegalese photographer, DIALO Photography.

CUTOUT-PORTRAITS_2 is a boy in a school sweater and tie on a smooth grey backdrop, the cleanest cutout of the
four. CUTOUT-PORTRAITS_4 has the backpack.

GROUP-CLASS_2 is a packed classroom with hands up and a chalkboard behind, the clearest single image of a
class that is engaged.

GROUP-YARD_2 is girls in blue uniforms running toward the camera. It has the most joy per pixel in the set.

GROUP-HIGHSCHOOL_1 is teenagers sharing a desk over exercise books.

SUCCESS_2 is a full ceremony: children in blue gowns and kente hats with adults in academic dress behind them.

TEACHER_1 is a teacher in African print at a green chalkboard with the alphabet on it.

SCHOOL-ADMIN_2 is a woman at a desk with a laptop and paperwork, reading a document. It reads as the person
who runs the school.

PARENT_3 is a father in a suit walking his son down a red-dirt road, shot from behind. It is the most honestly
West African frame in the set.

PARENT_2 is a mother on her own, smiling at her phone against a bright plain wall.

BOARDING_3 shows uniformed students working at desks, the best of the three boarding frames. BOARDING_1 and
BOARDING_2 come from a Nigerian boarding school and show the dormitory itself.

SCHOOL-BUILDINGS_3 is a drone frame of a school campus, built for the multi-site slide. SCHOOL-BUILDINGS_1 puts
a school block behind children playing football on the courtyard. SCHOOL-BUILDINGS_2 looks down a courtyard
between classroom blocks with students crossing the compound, which reads as a real West African school rather
than a stock campus.

ADMIN-WORKLOAD_1 is a desk buried in paper files with no people in it, which makes it easy to lay text over.

SCHOOL-BUS_1 shows children in the windows of a bus marked "Children of Hope".

CANTEEN_1 is a student with a plate of food among classmates, outdoors.

## Honest notes on the gaps

Senegalese school photography barely exists in the free stock libraries. Most of this set is Ghanaian,
Nigerian, Tanzanian and Ivorian schools, which look close enough for a West African deck but are not Dakar.
HERO-COVER_1 is the exception, shot in Senegal.

BOARDING is the slot where the libraries failed outright. There is no modern, well-lit photograph of an
African boarding school dormitory on Unsplash or Pexels. BOARDING_1 and BOARDING_2 come from Wikimedia
Commons (Olashore International School, Nigeria, CC BY-SA 4.0, by Bolatitocharles) and show the real thing
with on-camera flash. BOARDING_3 covers the evening study half of the slot with a much better photograph.

GROUP-HIGHSCHOOL_2 has teenagers reading together outdoors rather than around a table. GROUP-HIGHSCHOOL_1
carries the slot.

## Sources and credit

29 files come from Pexels, 3 from Unsplash and 2 from Wikimedia Commons. sources.csv records the exact photo
page for every file, so any credit can be checked or completed in a click.

Photographer names were read off the source pages. Pexels does not publish an author on every page, so 14 of the
34 rows name the photographer and the rest credit "Pexels". Open the source URL to see who shot it. The two
Commons frames are CC BY-SA 4.0 by Bolatitocharles and need that credit if they are published.

## Regenerating the contact sheets

The sheets were built with Pillow from the files in photos/. Thumbnails are 520 px wide, labelled with the
filename and the pixel dimensions. Rebuild a single slot by dropping or replacing files in its folder and
re-running the sheet builder.
