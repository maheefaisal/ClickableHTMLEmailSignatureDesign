# Email Signature Template with Tailwind CSS

This repository provides a responsive and customizable email signature template built with [Tailwind CSS](https://tailwindcss.com/). The template is designed to be easily integrated into your emails, offering a professional and modern appearance across various email clients.

## Features

- **Responsive Design**: Ensures the email signature displays correctly on both desktop and mobile devices.
- **Customizable Layout**: Easily modify the template to include your personal information, social media links, and company logo.
- **Tailwind CSS Integration**: Utilizes Tailwind CSS for efficient styling, allowing for quick customization and a consistent design system.

## Preview

![Email Signature Preview](https://i.ibb.co.com/BgQ5hmt/picofme-1.png)

## Getting Started

To integrate this email signature into your emails:

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/yourusername/email-signature-tailwind.git
   ```


2. **Customize the Template**:
   - Open the `index.html` file in your preferred code editor.
   - Replace placeholder text (e.g., name, job title, contact information) with your personal details.
   - Update the social media links with your profiles.
   - Add your company logo by replacing the existing image source URL.

3. **Inline CSS for Email Clients**:
   Many email clients require inline CSS for proper styling. To generate an inlined HTML file:
   - Install [Mailwind](https://github.com/soheilpro/mailwind):
     ```bash
     npm install -g mailwind
     ```
   - Run the following command to generate the inlined HTML:
     ```bash
     mailwind --input-html index.html --output-html email-signature.html
     ```

4. **Add to Your Email Client**:
   - Open your email client's signature settings.
   - Paste the contents of `email-signature.html` into the signature editor.
   - Save your changes.

## Customization

- **Profile Image**: Replace the `src` attribute of the `<img>` tag within the `.profile-image` div with the URL of your desired profile picture.
- **Contact Information**: Modify the text content and `href` attributes of the contact details to reflect your actual contact information.
- **Social Media Links**: Update the `href` attributes of the social media anchor tags with your personal social media URLs.
- **Company Logo**: Replace the content within the `.company-logo` div with your company's logo image and adjust the styling as needed.

## Dependencies

- [Tailwind CSS](https://tailwindcss.com/): A utility-first CSS framework used for styling the template.
- [Mailwind](https://github.com/soheilpro/mailwind): A tool to inline CSS for HTML emails, ensuring compatibility across various email clients.

## Resources

- [Maizzle](https://maizzle.com/): A framework for building HTML emails with Tailwind CSS, offering advanced email-specific post-processing. citeturn0search0
- [Meraki UI](https://merakiui.com/components/marketing/email-templates): Provides ready-to-use Tailwind CSS email template components for quick customization. citeturn0search2
- [Tailkits](https://tailkits.com/blog/free-tailwind-email-templates/): A collection of free Tailwind CSS email templates to enhance your email designs. citeturn0search9

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Tailwind CSS for providing a flexible and efficient styling framework.
- Mailwind for simplifying the process of inlining CSS in HTML emails.
- The open-source community for their continuous contributions and support.

By following the steps above, you can create a personalized and professional email signature that enhances your email communications. 