## Features
<details><summary>
  
### App Features
</summary>
  
- [x] ~Option to enable/disable word hover~
- [x] ~Option to customize hover details (can enable/disable particular things, like transliteration, translation, tajweed rules, etc)~
- [x] ~Add mulitple languages in word hover~
- [x] ~Add intuitive way to go to a specific verse~
- [x] ~Add nuzool order sort in Surah list (according to these sites https://tanzil.net/docs/revelation_order & https://ia800708.us.archive.org/1/items/HistoryOfQuran/History-of-Quran.pdf)~
- [x] ~Full verse transliteration~
- [ ] Add regional sources (IndoPak, etc)
- [ ] Add searching capability by Quranic Arabic/Transliteration/Language
- [ ] Audio
- [ ] Data annotation and commiting  portal
- [ ] Add Rabbana duas
- [ ] Add Tawdeeh ul Masail
- [ ] Create tajweed engine
</details>
<details><summary>

### Translations (expand to see more)
</summary>

- [x] ~Add en.ahmedali~
- [x] ~Add fa.gharaati~
- [x] ~Add fa.makarem~
- [x] ~Add ur.najafi~
- [x] ~Add ur.qadri~
- [x] ~Add ur.farmanali~
</details>
<details><summary>
  
### Tafsir (expand to see more)
</summary>

- [x] ~Add Tafsir-e-Namoona(Grand Ayatollah Naser Makarem Shirazi)~
- [ ] Add Tafsir-ul-Mizan(Allamah Sayyid Muhammad Husayn Tabataba'i)
- [ ] Add Tafsir-e-Burhan(Sayyid Hashim al-Bahrani)
- [ ] Add Tafsir-e-Rehnuma(Ayatollah Ali Akbar Hashemi Rafsanjani)
- [ ] Add Tafsir-ul-Kashif(Allama Sheikh Muhammad Jawad Mughniyah)
- [ ] Add Tafseer-e-Nur(Ayatullah Sheikh Mohsin Qara'ati)
</details>
<details><summary>
  
### Sahifah (expand to see more)
</summary>

- [ ] Add Sahifah al-Muhammadiyya
- [ ] Add Sahifah al-Alawiyya
- [ ] Add Sahifah al-Fatimiyya
- [ ] Add Sahifah al-Hasaniyya
- [ ] Add Sahifah al-Husayniyya
- [ ] Add Sahifah al-Sajjadiyya
- [ ] Add Sahifah al-Baqiriyya
- [ ] Add Sahifah al-Ja'fariyya
- [ ] Add Sahifah al-Kazimiyya
- [ ] Add Sahifah al-Radhaviyya
- [ ] Add Sahifah al-Jawadiyya
- [ ] Add Sahifah al-Hadiyya
- [ ] Add Sahifah al-Askariyya
- [ ] Add Sahifah al-Mahdiyya
</details>

## Bugs to Fix | Changes to Make
- [ ] PWA -> top bugs back to white when switching themes
- [ ] PWA -> top color isnt consistant with quran reader header
- [ ] PWA -> top has border when moving from dark theme to sepia
- [ ] DATA -> The translator's name should be in the language that they translated in
- [ ] DATA -> Populate ur.farmanali to 100%
- [ ] APP -> decide about feature/daily-infographic
- [ ] APP -> Change the mobile keyboard for side panel search
- [ ] APP -> Add bundling urdu font Jameel Noori Nastaleeq
- [ ] ORG -> Change Organization data structure to individual repos for each data source. Main data repo will pull release files. Source repos will only run pipeline once or when needed, then will only be maintained
- [x] ~Fix the initial load not working thingy (delay thingy)~
- [x] ~Fix the verse selector not working on mobile~
- [x] ~Remove lang mark from wbw hover~
- [x] ~Remove Tafsir ul Mizan button from library~
- [x] ~Refactor the Verses to add Tafsir & Mafaheem below the verse~
- [x] ~Translations should follow a queue based system, whichever is clicked first it displayed first.~
- [x] ~Make the settings sections collapsible~
- [x] ~Fix the sticky surah search and verse selector not fixed properly in surah dropdown (back is visible)~
- [x] ~Fix surah list not opening when clicking quran from library~
- [x] ~When tajweed is off, the word hover still shows the tajweed rules per word~
- [x] ~Change Verse font in Ayat of the Day~
- [x] ~Ayat not showing in Tafsir Sheet~
- [x] ~Change PWA top to be same color as header color~
- [x] ~App header is slightly transparent, remove transparency~
- [x] ~App theme resets in Quran reader when refreshing~
- [x] ~Center Allign -> Right Allign~
- [x] ~Make right allign default~
- [x] ~Rename Quran Reader to Quran in Quick Links~
- [x] ~Increase the recently opened tabs from 4 to 12~
- [x] ~In the tafsir selector drop down, remove the [language] in golden border, and just use what is being shown on the selection. Like Tafsir-e-Namuna English~
- [x] ~Refactor Home page (Dynamic Fluid Search bar replacing header, change the daily spiritual, Option to move to Quran directly from Home)~
- [x] ~Fix the tafsir of the same name but different language appear with the same name~
- [x] ~Change spans to lucide icons~
- [x] ~Change the surah picker, not at current surah~
- [x] ~Update quran render spacing~

## Ideas
- [ ] Tafsir Comparision
- [ ] Play tutorial for first time joining
- [ ] Something to do with Moon (Sighting)
- [ ] Islamic Timeline + Historical Map
- [ ] Change Quranic verses data scheme (for RAG-ability and tagging) to enable Semantic Search
