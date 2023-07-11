def generate_profile():
    """
    Generates the content for the GitHub profile README.
    """
    html_code = '''
    <html>
    <head>
        <style>
            body {
                font-family: Arial, sans-serif;
                background-color: #f5f5f5;
            }
            
            h1 {
                color: #333;
            }
            
            p {
                color: #666;
            }
            
            .linkedin-logo {
                display: inline-block;
                width: 50px;
                height: 50px;
                background-image: url("https://example.com/linkedin_logo.png");
                background-size: cover;
                vertical-align: middle;
            }
            
            .linkedin-link {
                color: #0077b5;
                text-decoration: none;
                margin-left: 10px;
            }
        </style>
    </head>
    <body>
        <h1>Aspiring System Administrator</h1>
        <p>
            I am Josh, a BSIT graduate, currently working as an IT Support professional in a Healthcare company. I am currently studying to become a system administrator in the future. I am currently reviewing for the MCSA, Azure Fundamentals, and AI Fundamentals certifications.
        </p>
        <div class="linkedin-logo"></div>
        <a class="linkedin-link" href="https://www.linkedin.com/in/joshuacruzcervantes/">Here's my LinkedIn profile</a>
    </body>
    </html>
    '''
    
    return html_code

# Generate the profile content
profile_content = generate_profile()

# Write the profile content to a README.md file
with open("README.md", "w") as file:
    file.write(profile_content)
