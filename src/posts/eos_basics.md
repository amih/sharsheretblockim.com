---
title: מבוא לאיאוס EOS
date: 2019-12-20
thumb: "much-to-do.jpg"
---
שרשרת בלוקים למתכנתים היא תשתית מחשובית לפיתוח אפליקציות ואני מקצר את התהליך של ההתלבטות והסקירה המייגעת של החלופות השונות. אגש ישר לעניין, אני מאמין שאיאוס היא הבחירה הנכונה לפיתוח פרויקטים לאו דווקא בהקשר של מטבעות קריפטוגרפיים, אלא סתם פרויקטים שצריכים טבלאות ונתונים ולנהל אותם בבסיס נתונים בענן המיוחד שנקרא שרשרת בלוקים.
 
יש הבדל בין איאוס שרשרת הבלוקים הראשית, EOS mainnet, ושרשרת בלוקים המבוססת על הקוד הפתוח של איאוס. פרויקט הקוד הפתוח של איאוס מאפשר לכל אחד להתקין שרשרת בלוקים ולנהל אותה בנפרד משרשרת הבלוקים הראשית ויש כבר כמה פרוייקטים מעניינים שמבוססים על איאוס, כל אחד עם הייחודיות שלו. כדי להבדיל בין השרשרת הראשית שנקראת איאוס לכל שרשרת אחרת, נהוג לקרוא לטכנולוגיה הכללית איאוס-איי-או, EOSIO. לא תמיד אני מקפיד על המינוח המדוייק.
 
איאוס נחשבת על ידי רבים לשרשרת בלוקים דור 3, כמובן שיש ויכוחים סוערים בין אנשים שאוהבים ומאמינים בטכנולוגיות אחרות, אך אלו מלחמות דת, בדומה למלחמות שהיו בעבר הרחוק בין OS/2 לבין Windows או בין שפות תכנות שונות. שרשרת בלוקים בטכנולוגיית איאוס בדרך כלל בעלת ביצועים גבוהים יותר משרשרת בלוקים דור ראשון כדוגמת ביטקוין ומשרשרת בלוקים דור שני כדוגמת איתריום. למשל זמן יצירת בלוק באיאוס הוא חצי  שניה בעוד בביטקוין הוא 10 דקות בממוצע ובאיתריום הוא 15 שניות בממוצע. בזמן שלוקח לביטקוין ליצור בלוק איאוס הוסיפה יותר מאלף בלוקים לשרשרת. ובעוד שבביטקוין יש שונות גדולה במרווחים בין הבלוקים, לפעמים יש בלוקים קרובים מאוד אחד לשני, בהפרש של פחות מדקה ובזמנים אחרים צריך לפעמים לחכות יותר מ 40 דקות לבלוק, באיאוס יש בלוק בדיוק כל חצי שניה, אלא אם יש תקלה טכנית אצל המחשב שתורו לייצר בלוקים, ואז צריך לחכות לבלוק הבא אצלו ומדלגים שניה שלמה או אם הוא בכלל לא זמין, צריך לחכות עד שייגמר תורו, 6 שניות שלמות.
 
היתרון של השימוש בשרשרת הראשית של איאוס הוא שהיא השרשרת הוותיקה ביותר בטכנולוגיה הזו והיא ציבורית ומבוזרת. החסרון הוא שצריך לקנות מטבעות ברשת כדי להתקין עליה תכנה והמחיר תנודתי. הרשת עדיין צעירה ויש תקופות בהן היא מתנהגת בצורה קיצונית, עמוסה מאוד או שהמשאבים בה יקרים לכמה ימים.
 
לעומת זאת, שרשרת פרטית שהוקמה על ידי המתכנת שמתקין עליה את הפרוייקט שלו, היא בבעלותו המלאה, כולל כל המטבעות (אסימונים) ואין משמעות למחיר המטבעות הללו, כי הם משמשים רק להקצאת משאבים לחלקים השונים של הפרוייקט שלו.
 
שרשרת בלוקים פרטית לא נהנית ממעמד של מאגר מידע מבוזר ללא שליט ריכוזי שיכול לצנזר בה מידע, אך זה כנראה בסדר בהרבה מקרים ויש עדיין יתרונות מעניינים לפלטפורמה הזו. שרשרת בלוקים פרטית יכולה להיות תחליף מעניין לשרת אינטרנט ולבסיס נתונים כשמקבלים יכולות של גיבוי חם כי כל המחשבים שמשמשים לניהול שרשרת הבלוקים מגבים אחד את השני כל הזמן. בנוסף, יש היסטוריה מלאה, לא רק של הפעולות שהמשתמשים עושים במערכת אלא גם של הפעולות שהמתכנתים עושים! יש תיעוד מלא של עדכוני תוכנה כולל תיקוני באגים ושדרוגים. 
 בכל פעם שמתכנת מעדכן חוזה חכם, הקוד מועלה ומתועד בשרשרת הבלוקים וניתן לראות בדיוק מה היו פעולות המשתמשים ובאיזה גירסה של הקוד הם השתמשו.
 
כיום אם רוצים תיעוד ברמה מלאה זה כמעט בלתי אפשרי. יש יותר מידי חלקים זזים במכונה כדי לרדוף אחרי כולם. גם אם מצליחים למפות את כל מה שצריך, נניח שהקוד שמור ב GIT, בסיס הנתונים מגובה פעם ביום בצורה מתגלגלת או פעם בשעה, מהר מאוד המציאות מתחילה להתרחק מהתמונה המושלמת, המתכנתים מוסיפים עוד יכולות, למשל העלאת קבצים של משתמשים או התממשקות בעזרת API למערכות אחרות.
 
החוכמה בגיבויים היא לתרגל לעיתים קרובות את השימוש בהם. אז מגלים את הפערים בין המצוי בגיבויים למה שצריך כדי לשחזר את כל המערכת.
 
שרשרת בלוקים פרטית מצריכה ידע בניהול השרתים וצריך להיות מודע לכל המרכיבים של המערכת. למשל, יש צורך בשטח אחסון של קבצים שהולך ועולה בהדרגה. כל בלוק שנוצר, גם אם לא בוצעו פעולות על ידי משתמשים לוקח קצת מקום בקובץ על הדיסק. אמנם מדובר על פחות מ 200 בתים אך זה קורה כל חצי שניה.
 
רגע, חושבים:
שני בלוקים בשניה, כפול 60 שניות בדקה, זה 120 בלוקים בדקה.
120 בלוקים בדקה כפול 60 דקות בשעה, זה 7200 בלוקים בשעה.
7200 בלוקים בשעה כפול 24 שעות ביממה, זה 172,800 בלוקים ביממה.
172,800 בלוקים ביממה כפול 365 ימים בשנה לא מעוברת, זה 63 מיליון 72 אלף בלוקים בשנה.
63,072,000 בלוקים בשנה כפול 200 בתים, זה 12GB.
 
גם אם שרשרת הבלוקים לא פעילה, היא תיקח 12GB של שטח אחסון בדיסק כל שנה. וצריך להכפיל בכמות השרתים שמגבים אחד את השני כל הזמן.
 
לפעמים הצלחה היא האויב האמיתי, מה קורה אם שרשרת הבלוקים הפרטית מצליחה וכולם משתמשים בה כל הזמן? זה המצב הקיצוני השני וגם אותו כדאי לחשב מראש. כל בלוק מוגבל לעד מגה בייט אחד ושוב, זה קורה כל חצי שניה. אז במקרה הזה:
 
63,072,000 בלוקים בשנה כפול מגה בייט, זה 66TB לשנה! דיסקים גדולים ויקרים אפילו ב AWS או שרות ענן אחר.
 
זה הזמן לחשוב על מעבר לשרתים פרטיים, עם כל הכאב ראש של ניהול המחשבים:
 
תקלות בדיסקים? בעיה שלך! זה לא הענן…
תקלות בלוח האם? בעיה שלך…
תקלות בתקשורת האינטרנט? בעיה שלך…
תקלות חשמל? יש לי אל פסק! החלפת מצברים במערכת האל-פסק? מה, יש תאריך תפוגה למערכת הזו?!
מיזוג? השרתים מפונקים, זה לא הנייד שלך שמספיק לו מאוורר קטן ואתה במשרד ממוזג כשאתה עובד.
 
מצד שני, לטובת זה שומרים את כל המערכת עם יתירות גבוהה על ידי שרתים שונים שמסתנכרנים כל הזמן אחד מהשני.
 
החישוב של עלות השרתים מראה ששרותי ענן יכולים להיות יקרים. שווה לבדוק אפשרות אירוח שרתים בחברות תקשורת. מסתבר שחוץ משרותי הענן המוכרים כמו AWS של אמזון או AZURE של מיקרוסופט או הענן של גוגל, יש עוד הרבה חברות טובות שמאפשרות לארח שרתים שאתם קונים אצלם. כך ניתן להנות משילוב של שרת עם כוננים גדולים במיוחד אך לא הכי יקרים כי אין צורך ממשי מיידי ביתירות, עם ראש שקט שהשרת נמצא במקום עם מייצבי מתח, מיזוג אוויר ושמירה פיזית. הייתי לאחרונה בסיור במתקן בפתח תקווה של חברת tripleC והיה מרשים מאוד.
 
אז זהו בינתיים לגבי התשתיות שאיאוס צריך. בהמשך אפרט יותר על מערכת ההרשאות והטבלאות שניתן לפתח על הפלטפורמה הזו והיתרונות והחסרונות לעומת מערכות אחרות.
