def generate_profile():
    """
    Generates the content for the GitHub profile README.
    """
    header = "### Aspiring System Administrator\n"
    body = "I am Josh, a BSIT graduate, currently working as an IT Support professional in a Healthcare company. I am currently studying to become a system administrator in the future. I am currently reviewing for the MCSA, Azure Fundamentals, and AI Fundamentals certifications.\n"
    linkedin_logo = "![LinkedIn Logo](https://example.com/linkedin_logo.png)"
    linkedin_link = "[Here's my LinkedIn profile](https://www.linkedin.com/in/joshuacruzcervantes/)"
    
    profile_content = f"{header}\n{body}\n\n{linkedin_logo}\n{linkedin_link}"
    return profile_content

# Generate the profile content
profile_content = generate_profile()

# Write the profile content to a README.md file
with open("README.md", "w") as file:
    file.write(profile_content)
