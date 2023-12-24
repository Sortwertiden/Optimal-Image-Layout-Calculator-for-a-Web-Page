# Optimal-Image-Layout-Calculator-for-a-Web-Page
Calculate optimal sizes and placement of images on a web page.
def image_layout_calculator(page_width, image_count):
    image_width = page_width / image_count
    image_height = 1.5 * image_width  # Example aspect ratio
    return image_width, image_height

page_width = float(input("Enter the width of the webpage: "))
image_count = int(input("Enter the number of images: "))
img_width, img_height = image_layout_calculator(page_width, image_count)
print(f"Optimal Image Size: {img_width} x {img_height}")
