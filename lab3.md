# Week 4 Lab Report 2
## `grep pattern file`

This command will grep the file that has the word that you type for pattern.
The specific pattern here is Honolulu, and the file is HandRHawaii.txt.

command:
```
$ grep Honolulu HandRHawaii.txt
```
output:
```
        Oahu (Including Honolulu)
        Aston Waikiki Sunset $$$ 229 Paoakalani Avenue, Honolulu, HI
        Halekulani $$$$ 2199 Kalia Road, Honolulu, HI 96815; Tel.
        Hilton Hawaiian Village $$$–$$$$ 2005 Kalia Road, Honolulu,
        Honolulu, HI 96815; Tel. (808) 923-1234 or (800) 233-1234; fax (808)
        half-hour drive of Honolulu. 387 rooms.
        Honolulu, HI 96816; Tel. (808) 739-8888 or (800) 367-2525; fax (808)
        Outrigger Reef $$$ 2169 Kalia Road, Honolulu, HI 96815; Tel.
        Pacific Beach Hotel $$$ 2490 Kalakaua Avenue,, Honolulu, HI
        Royal Hawaiian $$$$ 2259 Kalakaua Avenue, Honolulu, HI
        Honolulu, HI 96815; Tel. (808) 922-3111 or (800) 325-3535; fax (808)
        Honolulu, HI 96815; Tel. (808) 922-5811 or (800) 325-3535; fax (808)
        Sheraton Waikiki $$$–$$$$ 2255 Kalakaua Avenue, Honolulu,
```



This command will grep the file that has the word that you type for pattern.
The specific pattern here is hotel, and the file is HandRHongKong.txt.

command:
```
$ grep hotel HandRHongKong.txt
```
output:
```
        Hong Kong has some of the most luxurious hotels in the
        limited room service, and a wide range of facilities. Hong Kong hotels
        occupancy, with bath or shower. Unless otherwise noted, hotels take all
```

## grep -r pattern

This command will grep all the files in the directory that has the word that you type for pattern.
The specific pattern here is Airport, and it is in the directory `berlitz1`.

command:
```
$ grep -r Airport
```
output:
```
HandRHongKong.txt:        International Airport will be happy to arrange accommodations for you
WhatToDublin.txt:        the Dublin Airport will give you an instant refund as you depart. Some
WhatToJamaica.txt:        International Airport, the main airport of entry for Kingston and the
WhereToIndia.txt:        pass. Airports, railway stations, and hotels can be a pain anywhere in
WhereToIndia.txt:        Airport, the old turmoil of dockside porters and rickshaws that once
WhereToIndia.txt:        of Dabolim Airport, right down to the lovely and inviting Benaulim and
WhereToIsrael.txt:        alleyway. Airport-style security checks leave you in no doubt as to the
WhereToLosAngeles.txt:        (see page 81). Santa Monica Airport’s Museum of Flying displays vintage
WhereToMalaysia.txt:        the Bayan Lepas International Airport 18 km (11 miles) south from
WhereToMalaysia.txt:        international flights to Langkawi from Singapore and Kansai Airport in
```



This command will grep all the files in the directory that has the word that you type for pattern.
The specific pattern here is Museum, and it is in the directory `berlitz1`.

command:
```
$ grep -r Museum
```
output:
```
HandRHawaii.txt:        branch of the Bishop Museum in the Kalia Tower. Families love this
HandRJamaica.txt:        district of New Kingston and the Bob Marley Museum. Each room in this
HistoryHongKong.txt:        can get a glimpse into that past at Lei Cheng Uk Museum’s       
HistoryIstanbul.txt:        recorded on clay tablets on display in the Museum of the Ancient Orient
IntroDublin.txt:        holds the Museum of Modern Art. And Dublin, a city large in
IntroDublin.txt:        into their own with the new Museum of Modern Art and the many galleries
IntroFrance.txt:        dirty word it seems to be in so many other countries. Museums are as
IntroIsrael.txt:        Holocaust Museum) may give you an inkling of the capacity for tragedy
IntroJerusalem.txt:        performing at the Bible Lands Museum, or the echo of a soprano’s voice
WhatToDublin.txt:        given at Dublin’s Museum of Modern Art in the beautiful surroundings of
WhatToDublin.txt:        Sandycove, below the Joyce Museum, is the famous Forty Foot bathing
WhatToDublin.txt:        Museums that will appeal to children are the Fry Model
WhatToDublin.txt:        Railway Museum at Malahide Castle Estate (see page 75), while the  
WhatToDublin.txt:        National Wax Museum (Granby Row, Dublin 1; Tel. 872 6340) has a special
WhatToDublin.txt:        should enjoy the tour of Dublin Castle and the National Museum.    
WhatToHongKong.txt:        interest children of all ages. The Science Museum in Tsim Sha Tsui East
WhatToHongKong.txt:        while the nearby Space Museum has regular screenings on an enormous
WhatToIsrael.txt:        shops of the Israel Museum and the Tel Aviv Museum of Art are also
WhatToIsrael.txt:        Auditorium, Hubermann Street (tel. 03-528 9163), or the Tel Aviv Museum
WhatToIsrael.txt:        Diaspora Museum and Museum of Art in Tel Aviv and the Israel Museum in
WhatToJamaica.txt:        The first is Coyaba River Garden and Museum. Coyaba is the Arawak word
WhatToJamaica.txt:        Natural History Museum (on Tower Street), the oldest museum on the
WhatToJamaica.txt:        Bob Marley Museum and carefully managed by the Marley family to protect
WhatToJamaica.txt:        the battlements now guard Fort Charles Maritime Museum, which documents
WhatToJamaica.txt:        Museum, which displays a fascinating collection of finds from the 
WhatToJamaica.txt:        in 1925. The Jamaican People’s Museum of Craft and Technology, housed
WhatToJamaica.txt:        Museum comprises the most important collection of Arawak artifacts in
WhatToLakeDistrict.txt:        the Lakes at Lakeside, the Pencil Museum at Keswick, or the World of
WhatToLosAngeles.txt:        the Wells Fargo Theater at the Autry Museum of Western Heritage
WhatToLosAngeles.txt:        Downtown L. A.’s noted Children’s Museum (Tel.
WhatToLosAngeles.txt:        opening in 2005. The very participatory Kidspace Museum (Tel.  
WhatToLosAngeles.txt:        The Natural History Museum of Los Angeles County and its       
WhatToLosAngeles.txt:        the IMAX. The George C. Page Museum of La Brea Discoveries is another
WhereToDublin.txt:        small and eclectic Dublin Civic Museum (see page 58), an unassuming
WhereToDublin.txt:        Writers Museum).
WhereToDublin.txt:        Museum (see page 64). Tickets and advance notice are required for the
WhereToDublin.txt:        houses the Heraldic Museum and Genealogical Office, with exhibits on
WhereToDublin.txt:        Birthplace Museum (see page 66), 33 Synge Street, is marked by a plaque
WhereToDublin.txt:        following the signs, to the Irish-Jewish Museum in Walworth Road (see
WhereToDublin.txt:        artifacts that were found are on view in the National Museum (see page
WhereToDublin.txt:        Museum (see page 64).
WhereToDublin.txt:        in the Civic Museum. The north side of the building has statues by
WhereToDublin.txt:        Writers Museum (see page 59). The gallery is set in the 18th-century
WhereToDublin.txt:        alone, as well as for the splendid art collection. The Writers Museum
WhereToDublin.txt:        Museums and Galleries
WhereToDublin.txt:        Civic Museum
WhereToDublin.txt:        This branch of the National Museum of Ireland, opened in
WhereToDublin.txt:        Dublin Writers Museum
WhereToDublin.txt:        Transport Museum, souvenir shop, coffee shop, and a bar where you can
WhereToDublin.txt:        Irish-Jewish Museum
WhereToDublin.txt:        Irish Museum of Modern Art
WhereToDublin.txt:        National Museum of Ireland
WhereToDublin.txt:        Natural History Museum
WhereToDublin.txt:        Shaw Birthplace Museum
WhereToDublin.txt:        the National Transport Museum at Howth Castle (open June–August   
WhereToDublin.txt:        West of the harbor is the National Maritime Museum. The last stop on
WhereToDublin.txt:        James Joyce Museum
WhereToDublin.txt:        covers Irish Stud, Irish Horse Museum, and Japanese Gardens.      
WhereToDublin.txt:        Also here is the Fry Model Railway Museum, Ireland’s
WhereToEdinburgh.txt:        to Lady Stair’s House, now home to the Writers’ Museum. The house
WhereToEdinburgh.txt:        Next to the Writers’ Museum is James Court, built in the       
WhereToEdinburgh.txt:        Directly across High Street from Knox House is the Museum      
WhereToEdinburgh.txt:        Facing the Tolbooth is Huntly House Museum, the local
WhereToEdinburgh.txt:        The Museum of Scotland, with its main entrance on Chambers     
WhereToEdinburgh.txt:        Museum, a beautiful Victorian edifice with a large glass roof — much
WhereToEdinburgh.txt:        like a glass house. The Royal Museum has displays devoted to   
WhereToEdinburgh.txt:        café and gift shop. Tickets for the Museum of Scotland allow entrance
WhereToEdinburgh.txt:        also to the main collections of the Royal Museum, fulfilling the stated
WhereToEdinburgh.txt:        gallery and London’s Victoria and Albert Museum jointly purchased The
WhereToEdinburgh.txt:        are displayed in the Huntly House Museum in Edinburgh.
WhereToEgypt.txt:        House is here sharing a complex with the Modern Art Museum. Finally,
WhereToEgypt.txt:        The Egyptian Museum
WhereToEgypt.txt:        Museum built in 1902 as the Cairo Museum. Founded by French architect
WhereToEgypt.txt:        the gate leads to the Museum of Islamic Art, inaugurated in 1903 and
WhereToEgypt.txt:        You’ll be able to explore the Military Museum and Carriage
WhereToEgypt.txt:        Museum during your tour, but do take time to visit the vantage points
WhereToEgypt.txt:        The Gayer-Anderson Museum beside the Ibn Tulun mosque was
WhereToEgypt.txt:        The main attraction in Old Cairo is the Coptic Museum.
WhereToEgypt.txt:        harbor entrance. It houses the Naval Museum with a collection of relics
WhereToEgypt.txt:        the Greco-Roman Museum with a fine collection of both Roman, Greek, and
WhereToEgypt.txt:        Also on the riverside of El-Nil Street is the Mummy Museum,        
WhereToEgypt.txt:        of mummification. The “official” Archaeological Museum of Luxor lies a
WhereToEgypt.txt:        situ —  many others are on display in the Egyptian Museum in Cairo (see
WhereToEgypt.txt:        antechambers are now on show in the Egyptian Museum in Cairo (see page
WhereToEgypt.txt:        minutes’ walk from the hotel is the imposing Nubian Museum. With a 
WhereToFrance.txt:        of museums, the most important of which is the Musée de l’Armée (Museum
WhereToFrance.txt:        Museums
WhereToFrance.txt:        Other Major Museums
WhereToFrance.txt:        quaint cobbled streets. Museums, art galleries, and boutiques all add
WhereToFWI.txt:        (Also in Trois-Ilets: the Sugarcane Museum. )
WhereToFWI.txt:        Sainte-Marie houses a Rum Museum with documents and
WhereToFWI.txt:        Museum. ”
WhereToGreek.txt:        port will take you past the small Folklore Museum, with exhibits of
WhereToGreek.txt:        On higher ground behind the lake is the Museum of Delos.
WhereToGreek.txt:        in situ are reproductions — the originals sit in the Delos Museum. 
WhereToGreek.txt:        the Goulandris shipping family. They funded the Modern Art Museum, just
WhereToGreek.txt:        and other artifacts found on the island. The Megaron Gyzi Museum to the
WhereToGreek.txt:        walls is the Lesvos Archaeological Museum, with one of the finest  
WhereToGreek.txt:        Argenti Museum and Korai Library on Odos Korai Street, with its    
WhereToGreek.txt:        folklore and tradition. The Faltaïts Museum is housed in an old mansion
WhereToHawaii.txt:        The Bishop Museum is a repository of Hawaiiana and its
WhereToHongKong.txt:        House Museum of Tea Ware (see page 54). It’s in Hong Kong’s oldest
WhereToHongKong.txt:        buildings. The University’s Fung Ping Shan Museum, 94 Bonham Road (open
WhereToHongKong.txt:        Lane, where you’ll find the Museum of Medical Sciences (open    
WhereToHongKong.txt:        Next door is the Hong Kong Space Museum and Theatre (open       
WhereToHongKong.txt:        Hong Kong Museum of Art (see page 54) stands behind the Space Museum
WhereToHongKong.txt:        works from ancient sailing ships to the latest technology. The Museum
WhereToHongKong.txt:        Museum on Tonkin Road (open Monday–Wednesday and Friday–Saturday
WhereToHongKong.txt:        gold leaf. Also here is the Hongkong Heritage Museum (call Tel. 2180
WhereToHongKong.txt:        church, the Museum of Sacred Art houses a collection of sacramental
WhereToHongKong.txt:        The ambitious Museum of Macau (open Tuesday–Sunday
WhereToHongKong.txt:        Macau Cultural Center and the Museum of Art (open Tuesday–Sunday
WhereToHongKong.txt:        Macau’s oldest museum, the Maritime Museum
WhereToHongKong.txt:        interesting natural preserve with aNatural History Museum.      
WhereToIndia.txt:        Museums
WhereToIndia.txt:        National Museum, on Janpath (Queensway) just south of Rajpath, is worth
WhereToIndia.txt:        country’s early steam engines at the open air Rail Transport Museum. It
WhereToIndia.txt:        Nehru Memorial Museum is devoted to Independence and the
WhereToIndia.txt:        The Bharatiya Lokkala Mandal Folk Museum has an excellent display of
WhereToIndia.txt:        Museums
WhereToIndia.txt:        The Prince of Wales Museum, at the southern end of Mahatma
WhereToIndia.txt:        Museum, illustrates trends in modern Indian painting, including works
WhereToIndia.txt:        Elephanta Island; it belongs to the Victoria and Albert Museum nearby,
WhereToIndia.txt:        The Varanasi Hindu University has an Art Museum with a
WhereToIndia.txt:        Visitors will take delight in the Museum, which is a
WhereToIndia.txt:        which is simply and aptly named “the Indian Museum. ”
WhereToIndia.txt:        The Indian Museum, by Chowringhee and Sudder Street, makes
WhereToIndia.txt:        Patna Museum offers Mauryan sculpture: a stone yaksi
WhereToIndia.txt:        iconoclasts, so it’s worth visiting the Archaeological Museum, too,
WhereToIndia.txt:        government and the Indian Navy. There is a Military Museum and a   
WhereToIndia.txt:        The State Museum situated on Pantheon Road possesses
WhereToIsrael.txt:        fascinating small Islamic Museum. Take your time poring over the other
WhereToIsrael.txt:        Nearby is the Old Yishuv Court Museum, where you can
WhereToIsrael.txt:        Quarter Museum, in the remains of six mansions which somehow survived
WhereToIsrael.txt:        little farther along until you come to the landmark Rockefeller Museum,
WhereToIsrael.txt:        The Israel Museum and Farther West
WhereToIsrael.txt:        finest museum in the country, the Israel Museum. It’s a large complex,
WhereToIsrael.txt:        To get your bearings take the free daily Museum Highlights        
WhereToIsrael.txt:        Directly opposite is the Bible Lands Museum. It’s too much        
WhereToIsrael.txt:        to do this and the Israel Museum in a day, but students of Middle 
WhereToIsrael.txt:        Museum complex. It tells the story of the Holocaust in words, pictures,
WhereToIsrael.txt:        restaurants. Nearby, the Hagana Museum tells the fascinating story of
WhereToIsrael.txt:        Museum of Art houses an excellent collection of Israeli and European
WhereToIsrael.txt:        Tel Aviv University Museums
WhereToIsrael.txt:        The Beth Hatefutsoth, or Museum of the Diaspora (the
WhereToIsrael.txt:        buses 45 and 572 serve the Diaspora Museum and bus 89 will take you to
WhereToIsrael.txt:        the Eretz Israel Museum.
WhereToIsrael.txt:        the hill, is the Museum of Jaffa Antiquities. Return to Kedumin Square
WhereToIsrael.txt:        Nearby, the fine National Maritime Museum in Allenby
WhereToIsrael.txt:        the Clandestine Immigration and Naval Museum documents the defiance of
WhereToIsrael.txt:        a.m. ) and contains a museum. The Haifa Railway Museum, on Hativat
WhereToIsrael.txt:        For the Haifa Museum, take the Carmelit subway to
WhereToIsrael.txt:        Other places of interest are the Mane Katz Museum, Yefe
WhereToIsrael.txt:        Nof Street, the Prehistory Museum and Zoo, Ha-Tishbi Street, and the
WhereToIsrael.txt:        Ruben and Edith Hecht Museum of Archaeology, on the Haifa University
WhereToIsrael.txt:        Municipal Museum, which is actually no more than a well-preserved 
WhereToIsrael.txt:        structure, built by El-Jezzar (see page 57), nowadays holds the Museum
WhereToIsrael.txt:        on display in the excellent Shrine of the Book in the Israel Museum,
WhereToIstanbul.txt:        Topkapı Museums
WhereToIstanbul.txt:        Archaeological Museum (Arkeoloji Müzesi) has been expanded to include
WhereToIstanbul.txt:        The Museum of the Ancient Orient (Eski »ark Eserleri
WhereToIstanbul.txt:        Museum of Turkish and Islamic Arts (Türk ve Islam Eserleri Müzesi). The
WhereToIstanbul.txt:        the Hilton Hotel to the Military Museum (Askeri Müze). The fascinating
WhereToIstanbul.txt:        You can also visit the Sadberk Hanım Museum, with its
WhereToIstanbul.txt:        The town’s Museum of Turkish and Islamic Art (Türk ve
WhereToIstanbul.txt:        Berlin’s Pergamon Museum.
WhereToIstanbul.txt:        The Bergama Archaeological Museum, with a large collection      
WhereToIstanbul.txt:        stands the Archaeological Museum, whose superb collection of    
WhereToIstanbul.txt:        the Agora of ancient Smyrna. The Ethnographic Museum, opposite, 
WhereToIstanbul.txt:        Artemis, now on display in the Selçuk Museum. The marble-paved Street
WhereToIstanbul.txt:        antiquities, including a fascinating Museum of Underwater Archaeology.
WhereToIstanbul.txt:        the originals are in the British Museum in London.
WhereToItaly.txt:        Hall). These two palazzos house the Capitoline Museums (see page 66),
WhereToItaly.txt:        the Vatican Museums on separate days to avoid fatigue and visual   
WhereToItaly.txt:        Vatican Museums are made up of eight museums, five galleries, the  
WhereToItaly.txt:        Pio-Clementino Museum has assembled a wonderful collection of Roman and
WhereToItaly.txt:        Other Museums
WhereToItaly.txt:        The Capitoline Museums, in the twin palaces of the
WhereToItaly.txt:        from the National Museum, housed in the fine 15th-century
WhereToItaly.txt:        The Archaeological Museum includes important bronze statues of warriors
WhereToItaly.txt:        cherished treasure in the Santa Croce Museum is Cimabue’s 13th-century
WhereToItaly.txt:        the Bargello Museum (Via del Proconsolo, 4) was Florence’s first town
WhereToItaly.txt:        Bargello, before becoming the National Museum of Sculpture. The old
WhereToItaly.txt:        Museum (Museo degli Argenti), occupies 16 sumptuously decorated rooms
WhereToItaly.txt:        porcelain, and Baroque furniture. The Carriage Museum (Museo delle 
WhereToItaly.txt:        exterior never lets you suspect. The restoration of the Costume Museum
WhereToItaly.txt:        beginnings in the Etruscan Guarnacci Museum (Via Don Minzoni, 15). The
WhereToItaly.txt:        In the neighboring Cathedral Museum (Museo dell’Opera
WhereToItaly.txt:        The Cathedral Museum in the Palazzo Soliano includes other
WhereToItaly.txt:        Franchetti Museum. Italy’s most impressive post office, Fondaco dei
WhereToItaly.txt:        the merchants of Constantinople, now the Natural History Museum. It
WhereToItaly.txt:        Art Museum. Come back early in the morning to the covered 20th-century,
WhereToItaly.txt:        Museum of Roman, early Christian, and Byzantine Sculpture.
WhereToItaly.txt:        Cathedral Museum, which displays fine examples of Gothic sculpture from
WhereToItaly.txt:        the Science Museum (Museo della Scienza e della Tecnica) housed in a
WhereToItaly.txt:        The Brera and Other Museums
WhereToItaly.txt:        The Poldi-Pezzoli Museum (Via Manzoni 12) is a small,
WhereToItaly.txt:        Maria Cristina of France. It now houses the Civic Museum of Ancient Art
WhereToItaly.txt:        delle Scienze, is the Egyptian Museum (Museo Egizio), second in    
WhereToItaly.txt:        Museum traces its history in the Casa delle Guide (Maison des Guides).
WhereToItaly.txt:        The Museums
WhereToItaly.txt:        Archaeological Museum (Museo Archeologico Nazionale) is in no way a dry
WhereToItaly.txt:        The Capodimonte Museum, reopened in 2000, is housed in a
WhereToItaly.txt:        and adults adore the Museum of Nativities (Museo di Presepi),      
WhereToItaly.txt:        art, are exhibited at Naples’ Archaeological Museum (see page 173),
WhereToItaly.txt:        Museum (Piazza Olivella) displays superb statues and sculpted metope
WhereToItaly.txt:        church of San Nicola, the small but important Archaeological Museum has
WhereToJapan.txt:        modern Tokyo. Also on the grounds are the Museum of Imperial       
WhereToJapan.txt:        would also include the National Theater, and the National Museum of
WhereToJapan.txt:        No visitor here should miss the Tokyo National Museum, a
WhereToJapan.txt:        Nor should you neglect the National Museum of Western Art,
WhereToJapan.txt:        Shitamachi Customs and Manners Museum. Budget some time here: it will
WhereToJapan.txt:        Center Building. The Silk Museum on the second floor, with its     
WhereToJapan.txt:        Nearby is the Yokohama Museum of Art, designed by Tange
WhereToJapan.txt:        Municipal Museum of Modern Art houses a collection of Japanese oil 
WhereToJapan.txt:        (National Treasure Museum) has a fine collection of objects from   
WhereToJapan.txt:        Open Air Museum (Chokoku no mori, or “Forest of Sculptures) at     
WhereToJapan.txt:        Science Museum, which has some uninspiring audio-visual presentations
WhereToJapan.txt:        Museum of Traditional Industry presents a diverse collection of    
WhereToJapan.txt:        door, the National Museum of Modern Art is, despite its name, mainly
WhereToJapan.txt:        Museum, which houses the country’s largest collection of Japanese  
WhereToJapan.txt:        Just south of the National Museum is the spectacular
WhereToJapan.txt:        Miho Museum. Some 30 km (18.5 miles) outside Kyoto, set
WhereToJapan.txt:        deep in a forested nature preserve, is the Miho Museum, designed by
WhereToJapan.txt:        Museum of National Treasures, a fireproof repository built in 1958 to
WhereToJapan.txt:        Museum (50 Noboriojicho; Tel. (0742) 22-7771; open 9am–4:30pm daily
WhereToJapan.txt:        Museum, which has a fine collection of Chinese and Japanese paintings
WhereToJapan.txt:        For more ceramics, stop in at the Museum of Oriental
WhereToJapan.txt:        The nearby Osaka Municipal Art Museum, near Tennoji
WhereToJapan.txt:        and restaurants that also contains the Suntory Museum. In addition to
WhereToJapan.txt:        look at the marvelous samples in the Municipal Art Museum in the park
WhereToJapan.txt:        Museum documents the horror with charts, models, photographs, videos,
WhereToJapan.txt:        The excellent Folk Craft Museum in an old manor house
WhereToJapan.txt:        visiting Yufuin’s Museum of Modern Art, the unexpected Marc Chagall
WhereToJapan.txt:        Museum, and 15 other art galleries. The gentle paths along the small
WhereToJapan.txt:        Museum, which includes local arts and crafts as well as examples of
WhereToJapan.txt:        Satsuma had his villa. Be sure to visit the Shoko Shuseikan Museum,
WhereToJapan.txt:        Chiran’s Kamikaze Museum, which includes a monumental
WhereToJapan.txt:        fascinating Aso Volcanic Museum. This has some very realistic      
WhereToJapan.txt:        provocative and challenging Atomic Bomb Museum. The exhibits powerfully
WhereToJapan.txt:        traditional arts and crafts. The superb Ainu Museum, established with
WhereToJerusalem.txt:        on the western hills of the city, the dynamic Israel Museum, the
WhereToJerusalem.txt:        powerful Yad Vashem Holocaust Memorial and Museum, and the contemporary
WhereToJerusalem.txt:        Inside the Tower of David, the Museum of the History of Jerusalem has
WhereToJerusalem.txt:        19th century, pay a visit to the exhibit at the Old Yishuv Court Museum
WhereToJerusalem.txt:        to the left and, today, the focus of the Roman Gate Museum.    
WhereToJerusalem.txt:        the Rockefeller Archaeological Museum, which is perched on a hill (see
WhereToJerusalem.txt:        Israel Museum, the Knesset (Israel’s Parliament), and the ministries
WhereToJerusalem.txt:        The Wolfson Museum is upstairs, exhibiting an exceptional collection of
WhereToJerusalem.txt:        are the pavilions of the extraordinary Israel Museum, which comprises
WhereToJerusalem.txt:        state-of-the-art Bible Lands Museum, with its collection of beautiful
WhereToLakeDistrict.txt:        North of the town, Windermere Steamboat Museum looks back   
WhereToLakeDistrict.txt:        Ghyll Water Mill. The Armitt Library and Museum Centre, just a little
WhereToLakeDistrict.txt:        friends. Behind the cottage, the Wordsworth Museum displays many of
WhereToLakeDistrict.txt:        the Museum of Rural Life. From 1778 to 1787 Wordsworth was a pupil at
WhereToLakeDistrict.txt:        Lakeland Motor Museum on the grounds has around 100 exhibits of various
WhereToLakeDistrict.txt:        and Museum of Lakeland Life complex. The main house, built in 1759,
WhereToLakeDistrict.txt:        the current program. The Museum, situated in the renovated stable block
WhereToLakeDistrict.txt:        The Kendal Museum of Archaeology and Natural History, near  
WhereToLakeDistrict.txt:        grounds, including a Fell Pony Museum and the Yeoman’s Museum.
WhereToLakeDistrict.txt:        but the Pencil Museum provides fascinating insights into the history of
WhereToLakeDistrict.txt:        The Keswick Museum and Art Gallery in Fitz Park is a        
WhereToLakeDistrict.txt:        The Working Museum of Printing is also on Main Street; the  
WhereToLakeDistrict.txt:        site are a Motor Museum and the Cumberland Toy and Model Museum, which
WhereToLosAngeles.txt:        TV production, visit the Hollywood Entertainment Museum (7021 Hollywood
WhereToLosAngeles.txt:        unimpressive Hollywood Wax Museum, which features a collection of
WhereToLosAngeles.txt:        satin bras and panties is their renowned “Lingerie Museum,” where you
WhereToLosAngeles.txt:        date back 40,000 years. In the large pit in front of the Page Museum
WhereToLosAngeles.txt:        The adjacent George C. Page Museum of La Brea Discoveries     
WhereToLosAngeles.txt:        Museum Row
WhereToLosAngeles.txt:        The Los Angeles County Museum of Art (5905 Wilshire
WhereToLosAngeles.txt:        The small but significant Craft and Folk Art Museum, at       
WhereToLosAngeles.txt:        Nearby, at 6060 Wilshire, at Fairfax, the Petersen Automotive Museum
WhereToLosAngeles.txt:        Opened in 1993, the Museum of Tolerance (9786 West Pico       
WhereToLosAngeles.txt:        tip, the UCLA/Armand Hammer Museum of Art and Cultural Center (10899
WhereToLosAngeles.txt:        attractions in one, the Center comprises the J. Paul Getty Museum plus
WhereToLosAngeles.txt:        institutes for arts education, conservation, and research. The Museum
WhereToLosAngeles.txt:        Monica Museum of Art, which showcases the avant-garde and performance
WhereToLosAngeles.txt:        galleries of the California Heritage Museum (2612 Main Street). This
WhereToLosAngeles.txt:        (see page 81). Santa Monica Airport’s Museum of Flying displays vintage
WhereToLosAngeles.txt:        Santa Monica Museum of Art (tel. 310-586-6488)
WhereToLosAngeles.txt:        was the J. Paul Getty Museum (17985 Pacific Coast Highway), now called
WhereToLosAngeles.txt:        the new Museum at the Getty Center in Brentwood (see page 39).
WhereToLosAngeles.txt:        attending the opera or going to the Museum of Contemporary Art. But
WhereToLosAngeles.txt:        center, a theater, and the Japanese American National Museum (369 East
WhereToLosAngeles.txt:        Downtown Museums
WhereToLosAngeles.txt:        The Museum of Contemporary Art, known as MOCA (250 S.
WhereToLosAngeles.txt:        The Natural History Museum (900 Exposition Boulevard) is      
WhereToLosAngeles.txt:        are offered at the California African-American Museum (600 State
WhereToLosAngeles.txt:        Adjacent is the (Gene) Autry Museum of Western
WhereToLosAngeles.txt:        The equally reputed Norton Simon Museum (at 411 West
WhereToLosAngeles.txt:        The Pacific Asia Museum (46 North Robles Avenue) has been     
WhereToLosAngeles.txt:        Down the road from Knott’s is the Movieland Wax Museum        
WhereToLosAngeles.txt:        the Hollywood Wax Museum, are accompanied by entertaining “Wax Facts. ”
WhereToLosAngeles.txt:        With a Wax Museum ticket, you can also visit the adjacent Ripley’s
WhereToMadeira.txt:        Museu de Arte Sacra (Museum of Sacred Art), housed in what was a 
WhereToMadeira.txt:        (Vicente Photography Museum). It is easy to miss, but once you have
WhereToMadeira.txt:        with Rua Mouraria is the Museu Municipal do Funchal (Municipal Museum),
WhereToMadeira.txt:        Museu de Arte Con­tem­poránea (Museum of Contemporary Art). Another
WhereToMadeira.txt:        lucrative industry is a Museum of Whaling and a few scrimshaw and
WhereToMadeira.txt:        Although the Museu da Baleia (Whale Museum) shows a video        
WhereToMadrid.txt:        Fernando — call it the Museum of the Royal Academy. It possesses a
WhereToMadrid.txt:        collection of paintings by Zurbarán, rivaling that of the Prado Museum.
WhereToMadrid.txt:        Highlights of the Prado Museum
WhereToMadrid.txt:        Museum of Modern Art in New York until the death of Franco, per the
WhereToMadrid.txt:        Toros y Museo Taurino (Bullfighting Ring and Museum), officially called
WhereToMadrid.txt:        the Museo de Santa Cruz (Museum of the Holy Cross) is housed in the
WhereToMadrid.txt:        into a church. Today the Museo Sefardí (Sephardic Museum) is attached
WhereToMadrid.txt:        to the Museo de Caza (Hunting Museum), with stuffed animals and ancient
WhereToMalaysia.txt:        Besar, which now houses the Textile Museum.
WhereToMalaysia.txt:        The Muzium Negara (National Museum) stands on Jalan
WhereToMalaysia.txt:        Other museums include the National History Museum on Jalan      
WhereToMalaysia.txt:        Police Museum (1961) on Jalan Semarak highlights the war against the
WhereToMalaysia.txt:        the campus of the University of Malaysia is the Asian Art Museum, with
WhereToMalaysia.txt:        have a Natural Rubber Museum, which opened since 1992 at the Rubber
WhereToMalaysia.txt:        Geological Museum on Jalan Sultan Azlan Shah. In addition to exhibits
WhereToMalaysia.txt:        the Darul Ridzuan Museum, housed in the former home of wealthy tin
WhereToMalaysia.txt:        traditional timbered Istana Kenangan, now used as a Royal Museum. This
WhereToMalaysia.txt:        Built in 1886, the Perak Museum, housing an interesting
WhereToMalaysia.txt:        citadel. Since 1980 the building has housed the Museum of Ethnography
WhereToMalaysia.txt:        the Maritime Museum, is housed in a model of the Flor De La Mar, a
WhereToMalaysia.txt:        Baba Nyonya Heritage Museum, an amalgam of three houses belonging to
WhereToMalaysia.txt:        Penang Museum and Art Gallery at the corner of Lebuh Light and Lebuh
WhereToMalaysia.txt:        Archaeological Museum.
WhereToMalaysia.txt:        State Museum, about 15 minutes by car just north of the city, was built
WhereToMalaysia.txt:        Across the square is the Bank Kerapu (War Museum), housed       
WhereToMalaysia.txt:        The Istana Jahar (Royal Customs Museum) was built in 1887,      
WhereToMalaysia.txt:        near the Tourist Information Centre, is the Kelantan State Museum, with
WhereToMalaysia.txt:        accessible from the river — is the State Museum, housed in a    
WhereToMalaysia.txt:        marble of the Sultan Abu Bakar Mosque, the Royal Museum, and the Istana
WhereToMalaysia.txt:        Chinese History Museum are near the group of grand, five-star hotels
WhereToMalaysia.txt:        to Fort Margherita, now the Muzium Polis (Police Museum). The   
WhereToMalaysia.txt:        Sawarak Museum, which has one of the best collections of folk art and
WhereToMalaysia.txt:        Within the Museum’s grounds there is an Aquarium, the
WhereToMalaysia.txt:        Indonesia. Adjacent to the new wing of the Sarawak Museum is the Muzium
WhereToMalaysia.txt:        Islam (Islamic Museum).
WhereToMalaysia.txt:        Kuching also claims the world’s first Cat Museum, in honor      
WhereToMalaysia.txt:        Museum,” it provides an opportunity for the traveler short on time to
WhereToMalaysia.txt:        1870s, but it was not until 1958 that local explorer and Sarawak Museum
WhereToMalaysia.txt:        found nearby are on display at the Kuching Museum.
WhereToMalaysia.txt:        come into town from the airport. Nearby is the Sabah State Museum on
WhereToMalaysia.txt:        Jalan Museum, which is open only from Saturday to Thursday. The Museum
WhereToMalaysia.txt:        beyond, museums, including the Asian Civilization Museum, the National
WhereToMalaysia.txt:        Museum, and the Singapore Art Museum.
WhereToMalaysia.txt:        The venerable National Museum, on Stamford Road just
WhereToMallorca.txt:        Museum next door, a treasure-trove of silver monstrances and   
```





