# Οδηγός Deployment

## GitHub + Render (Static Site)

### Βήμα 1: GitHub
1. Δημιούργησε λογαριασμό στο https://github.com αν δεν έχεις
2. Πάτα **New repository** → δώσε όνομα π.χ. `kodoquestapp`
3. Κάνε το repository **Public**
4. Ανέβασε τα αρχεία: `index.html`, `README.md`

### Βήμα 2: Render
1. Δημιούργησε λογαριασμό στο https://render.com (δωρεάν)
2. Πάτα **New → Static Site**
3. Σύνδεσε το GitHub repository σου
4. Στις ρυθμίσεις:
   - **Publish directory:** `.` (τελεία)
   - **Build command:** (άφησε κενό)
5. Πάτα **Create Static Site**

Μετά από ~1 λεπτό το παιχνίδι είναι online!
