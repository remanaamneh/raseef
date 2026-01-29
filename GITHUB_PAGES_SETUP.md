# הוראות להעלאה ל-GitHub Pages

## שלב 1: העלאת הקבצים ל-GitHub

### אפשרות א': דרך GitHub Web Interface

1. לך ל-https://github.com/remanaamneh/raseef
2. לחץ על "Add file" > "Upload files"
3. גרור את כל התיקייה `alrasif-menu-site-v58-waffle-menu-updated` (או את כל הקבצים מתוכה)
4. לחץ על "Commit changes"

### אפשרות ב': דרך Git Command Line

```bash
cd alrasif-menu-site-v58-waffle-menu-updated
git init
git add .
git commit -m "Initial commit - Menu website"
git branch -M main
git remote add origin https://github.com/remanaamneh/raseef.git
git push -u origin main
```

## שלב 2: הפעלת GitHub Pages

1. לך ל-https://github.com/remanaamneh/raseef
2. לחץ על "Settings" (בתפריט העליון)
3. גלול למטה לחלק "Pages" (בתפריט השמאלי)
4. תחת "Source", בחר:
   - Branch: `main` (או `master`)
   - Folder: `/ (root)`
5. לחץ על "Save"
6. חכה 1-2 דקות עד שהאתר יעלה

## שלב 3: קבלת כתובת ה-URL

לאחר ההפעלה, האתר יהיה זמין בכתובת:
**https://remanaamneh.github.io/raseef/**

## שלב 4: בדיקת ה-QR Code

1. פתח את האתר בכתובת: https://remanaamneh.github.io/raseef/
2. לחץ על כפתור "📱 QR Code"
3. סרוק את ה-QR Code עם הטלפון שלך
4. האתר יפתח בטלפון!

## הערות חשובות

- ודא שכל הקבצים בתיקייה `alrasif-menu-site-v58-waffle-menu-updated` הועלו
- הקבצים צריכים להיות ב-root של ה-repository (לא בתיקייה נוספת)
- אם האתר לא עובד, בדוק ב-Settings > Pages שההגדרות נכונות

## עדכון האתר

כל פעם שתעדכן קבצים:
1. העלה את הקבצים החדשים ל-GitHub
2. GitHub Pages יעדכן אוטומטית תוך 1-2 דקות
