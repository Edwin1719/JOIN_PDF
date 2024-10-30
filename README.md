# JOIN_PDF
![texto del vínculo](https://www.datasig.com.co/wp-content/uploads/2023/10/Unor-2-pdfs-con-python.png)

JOIN_PDF is a Python application designed to merge multiple PDF files into a single document. The application uses Streamlit for the user interface, PyMuPDF for handling PDF operations, and ngrok to create secure public URLs for easy sharing and testing. This project is ideal for anyone looking to streamline their document management tasks.


**FEATURES**

-**Install Dependencies:** Begin by installing the necessary libraries for the project. Use pip to install PyMuPDF, pyngrok, and Streamlit. These libraries are essential for PDF manipulation, creating secure tunnels, and building the web application interface, respectively.

-**Define the PDF Merging Function:** Create a Python function named unir_pdf that takes two arguments: the input folder path and the output file name. This function uses PyMuPDF to open each PDF file in the specified folder, merge them into a single PDF document, and save the result. This step ensures that all PDF files in the input folder are combined into one cohesive document.

-**Build the Streamlit Application:** Develop the user interface using Streamlit. This involves creating a simple web application where users can input the path to the folder containing the PDFs and specify the name of the output file. The interface includes text input fields for these parameters and a button to trigger the merging process. When the button is clicked, the unir_pdf function is called, and the merged PDF is created.

-**Configure ngrok:** Set up ngrok to create a secure public URL for the Streamlit application. First, authenticate ngrok with your authtoken using the command !ngrok authtoken "YOUR_NGROK_AUTHTOKEN". Then, create a tunnel to the local Streamlit server running on port 8501. This step allows you to share the application with others via a public URL, making it accessible for testing and use.

-**Run the Application:** Start the Streamlit application and ensure it runs in the background. Use the command !streamlit run app.py &>/content/logs.txt & to launch the application. Once the application is running, use ngrok to generate a public URL, which you can share with others. This step ensures that the application is live and accessible, allowing users to upload and merge PDF files through a web interface.


**TECHNOLOGIES USED**

-**Python:** Python is the primary programming language used to develop the application. It provides the necessary libraries and tools for PDF manipulation and web application development.

-**Streamlit:** Streamlit is a framework for creating interactive web applications in Python. In this project, it is used to build the user interface, allowing users to upload PDF files and initiate the merging process through a simple web interface.

-**PyMuPDF:** PyMuPDF is a library for PDF manipulation. It is used to open, read, combine, and save PDF files. This library handles all the necessary PDF operations to merge multiple files into a single document.

-**ngrok:** ngrok is a tool that creates secure tunnels to localhost. In this project, it is used to generate a secure public URL for the Streamlit application, making the application accessible from anywhere for testing and sharing purposes.


**DOCUMENTATION**

!https://products.aspose.com/words/es/python-net/merge/

! https://www.youtube.com/watch?v=vUl3FiyjVb4
