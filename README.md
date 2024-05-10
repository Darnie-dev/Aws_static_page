# Aws_static_page
This project involves deploying a static website using AWS S3 Bucket for storage and CloudFront for content delivery. Here are the steps:

1. **S3 Bucket Creation**: 
   - Create an S3 bucket to store the static website files.
     ![Image Alt Text](enter_s3.png)
     ![Image Alt Text](create_buck.png)
 
2. **Static Website Upload**:
   - Upload the static website files to the created S3 bucket.
     ![Image Alt Text](uploadfolder.png)
      
3. **CloudFront Distribution Creation**:
   - Set up a CloudFront distribution to serve the static website content.
     ![Image Alt Text](create_distro.png)
     ![Image Alt Text](distro_name.png)

4. **Origin Access Control (OAC)**:
   - Implement Origin Access Control to restrict access to the public.
   ![Image Alt Text](createOAC.png)

5. **Public Policy Addition**:
   - Add a policy to make the static website content publicly accessible.
   ![Image Alt Text](policy_code.png)
6. **Website Confirmation**:
   - Confirm the deployment by accessing the website using the CloudFront distribution domain name.
   ![Image Alt Text](dns.png)
   ![Image Alt Text](landing_page.png)

END
