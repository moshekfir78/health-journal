# יומן בריאות

אפליקציית יומן בריאות בעברית (אוכל, ספורט, שינה, מדדים) עם הקלדה קולית.

אחרי הגדרת מזהה OAuth, מתחברים עם Google והיומן נשמר בחשבון Google (באזור הנתונים של האפליקציה ב-Drive). עד אז הנתונים נשמרים במכשיר בלבד.

כדי להפעיל התחברות: יוצרים OAuth Web client ב-Google Cloud Console, מפעילים את Drive API, ומדביקים את המזהה ב-`index.html` בשורה `var GOOGLE_CLIENT_ID = '';`. מקור JavaScript מורשה: `https://moshekfir78.github.io`. הרשאה: `https://www.googleapis.com/auth/drive.appdata`.
