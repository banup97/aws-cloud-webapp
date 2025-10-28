# aws-cloud-webapp
Static website hosted on AWS S3 for cloud deployment

☁️ Task 6: Host a Static Website on AWS S3
🎯 Objective:

To learn how to host a static website using Amazon S3, including uploading HTML files, setting permissions, enabling static website hosting, and testing the website URL.

🧰 Prerequisites

AWS Account (Free Tier)

Basic understanding of HTML

"index.html" file created using Notepad.

⚙️ Step-by-Step Procedure

Step 1: Create a New S3 Bucket

1. Log in to your AWS Management Console.
2. Open the S3 service.
3. Click Create Bucket.
4. Enter a unique Bucket name (my-cloud-app-banupriya-2025).
5. Choose your Region (Asia-pacific-mumbai)
6. Uncheck Block all public access.
7. Tick the checkbox to acknowledge public access.
8. Click Create Bucket.

🖼️ Screenshot 1: Bucket creation page

Step 2: Upload Website Files

1. Click your newly created bucket.

2. Go to Objects → Upload → Add Files.

3. Select your index.html file.

4. Click Upload.

🖼️ Screenshot: Uploaded index.html

Step 3: Set File Permissions

1. After upload, select index.html.
  
2. Click Actions → Make public using ACL (or edit permissions under Object details).

3. Confirm the file is public.

🖼️ Screenshot: Object permissions

Step 4: Enable Static Website Hosting

1. In the bucket, go to Properties tab.

2. Scroll to Static website hosting section.

3. Click Edit → Choose Enable.

4. Select Host a static website.

5. Enter.

Index document: index.html

6. Click Save changes.

🖼️ Screenshot: Static website hosting section
Step 5: Get the Website URL

1. Scroll again to Static website hosting section.

2. Copy the Bucket website endpoint URL (http://my-cloud-app-banupriya-2025.s3-website.ap-south-1.amazonaws.com)

🖼️ Screenshot: Website URL copied

Step 6: Test Your Website

1. Paste the copied URL in your browser.

2. You should see your page content — e.g.,

> Hello Cloud!
This is my first web app hosted on AWS.

🖼️ Screenshot: Final website in browser

✅ Result:

You have successfully hosted a static website on Amazon S3 and made it publicly accessible.

🧠 Key Learnings

Hosting websites without servers using S3.

Managing object permissions and public access.

Understanding bucket policies and static hosting URLs.
