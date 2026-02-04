# Back To School Dress Offer

Professional email template for Back to School dress offer, targeting both educational institutions and retail sector.

![Thumbnail](./thumbnail.png)

## Template Details

- **Industries:** Retail, Education
- **Message Type:** Marketing
- **Tags:** sale, backtoschool, dressoffer

## Files
- `index.html`: The improved, localized, and branded HTML template.
- `template.blade.php`: Ready-to-use Laravel Blade template with `asset()` helpers.
- `assets/`: Directory containing localized images and styles used in the template.

## Usage in Laravel

### 1. Store the Template
Place the `index.html` content in a Blade view (e.g., `resources/views/emails/back-to-school-dress-offer.blade.php`).

### 2. Handle Assets
Move the content of `assets/` to your public directory (e.g., `public/vendor/mail-templates/back-to-school-dress-offer/`) and update the paths in the HTML to use the `asset()` helper.

### 3. Send Email
```php
Mail::to($user)->send(new \App\Mail\GenericEmail([
    'view' => 'emails.back-to-school-dress-offer',
    'data' => [
        // Your dynamic data here
    ]
]));
```

---
*Created with ❤️ by **[LaravelMail.com](https://laravelmail.com)** - Your source for professional email templates.*
