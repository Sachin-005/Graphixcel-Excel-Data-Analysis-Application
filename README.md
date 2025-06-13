<<<<<<< HEAD
# GRAPHIXCEL - Excel to Graph Converter

A modern Django web application that converts Excel and CSV files into beautiful, interactive graphs. Upload your data files and generate bar charts, line graphs, and pie charts with just a few clicks.

## Features

- 📊 **Multiple Graph Types**: Bar charts, line graphs, and pie charts
- 📁 **File Upload**: Support for Excel (.xlsx, .xls) and CSV files
- 🎨 **Modern UI**: Clean, professional interface with responsive design
- 🔄 **Real-time Processing**: Instant graph generation
- 📱 **Mobile Responsive**: Works perfectly on all devices
- 🎯 **User-friendly**: Intuitive interface with drag-and-drop functionality

## Screenshots

The application features a modern, professional interface with:
- Clean navigation bar with branding
- Hero section with gradient background
- Card-based layout for file upload and graph generation
- Professional color scheme and typography
- Responsive design for all screen sizes

## Installation & Setup

### Prerequisites

- Python 3.8 or higher
- pip (Python package installer)

### Step 1: Clone or Download the Project

```bash
# If using git
git clone <repository-url>
cd graphixcel

# Or download and extract the project files
```

### Step 2: Create a Virtual Environment (Recommended)

```bash
# Create virtual environment
python -m venv venv

# Activate virtual environment
# On Windows:
venv\Scripts\activate

# On macOS/Linux:
source venv/bin/activate
```

### Step 3: Install Dependencies

```bash
pip install -r requirements.txt
```

### Step 4: Run Database Migrations

```bash
python manage.py migrate
```

### Step 5: Start the Development Server

```bash
python manage.py runserver
```

### Step 6: Access the Application

Open your web browser and navigate to:
```
http://127.0.0.1:8000/
```

## How to Use

1. **Upload File**: Click on the file upload area or drag and drop your Excel/CSV file
2. **Select Graph Type**: Choose between Bar Graph, Line Graph, or Pie Chart
3. **Configure Axes**: 
   - For Bar/Line graphs: Select X-axis and Y-axis columns
   - For Pie charts: Select the column to analyze
4. **Generate Graph**: Click the "Generate Graph" button
5. **View Result**: Your graph will be displayed below the form

## Supported File Formats

- **Excel Files**: .xlsx, .xls
- **CSV Files**: .csv

## Project Structure

```
graphixcel/
├── graphixcel/          # Django project settings
│   ├── settings.py      # Project configuration
│   ├── urls.py          # Main URL routing
│   └── wsgi.py          # WSGI configuration
├── Main/                # Main application
│   ├── views.py         # View functions
│   ├── urls.py          # App URL routing
│   ├── graphGen.py      # Graph generation logic
│   └── models.py        # Database models
├── templates/           # HTML templates
│   └── index.html       # Main template
├── static/              # Static files
│   └── styles/
│       └── index.css    # CSS styles
├── media/               # Uploaded files and generated graphs
├── manage.py            # Django management script
├── requirements.txt     # Python dependencies
└── README.md           # This file
```

## Dependencies

- **Django**: Web framework
- **pandas**: Data manipulation and analysis
- **matplotlib**: Graph generation
- **plotly**: Interactive plotting (for future enhancements)
- **openpyxl**: Excel file reading
- **Pillow**: Image processing

## Troubleshooting

### Common Issues

1. **Import Error**: Make sure all dependencies are installed
   ```bash
   pip install -r requirements.txt
   ```

2. **Static Files Not Loading**: Ensure the static files are collected
   ```bash
   python manage.py collectstatic
   ```

3. **File Upload Issues**: Check that the `media` directory exists and has write permissions

4. **Graph Not Generating**: Verify that your Excel/CSV file has valid data and the selected columns exist

### Error Messages

- **"Couldn't import Django"**: Install Django using `pip install django`
- **"No module named 'pandas'"**: Install pandas using `pip install pandas`
- **"File not found"**: Ensure your file is in a supported format (.xlsx, .xls, .csv)

## Development

### Running in Development Mode

```bash
python manage.py runserver --settings=graphixcel.settings
```

### Making Changes

1. Modify the code as needed
2. Test your changes locally
3. Update the requirements.txt if you add new dependencies
4. Test the application thoroughly

## Production Deployment

For production deployment, consider:

1. **Environment Variables**: Set `DEBUG=False` and configure `SECRET_KEY`
2. **Database**: Use PostgreSQL or MySQL instead of SQLite
3. **Static Files**: Configure a proper static file server
4. **Security**: Set up HTTPS and configure `ALLOWED_HOSTS`
5. **Performance**: Use Gunicorn or uWSGI as the WSGI server

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## License

This project is open source and available under the MIT License.

## Support

If you encounter any issues or have questions, please:

1. Check the troubleshooting section above
2. Review the Django documentation
3. Create an issue in the repository

## Future Enhancements

- [ ] Interactive graphs with Plotly
- [ ] More graph types (scatter, histogram, etc.)
- [ ] Data preprocessing options
- [ ] Export graphs in different formats
- [ ] User authentication and saved graphs
- [ ] API endpoints for programmatic access 
=======
# 🚀 Graphixcel: Excel Data Analysis Application

**Graphixcel** is a Django-based web application designed to import, analyze, and visualize Excel data with ease. Whether you're crunching numbers or exploring trends, Graphixcel makes data analysis intuitive and interactive.

---

## ✨ Features

- **Excel file import**: Upload `.xlsx` or `.xls` files directly.
- **Automated data parsing**: Clean, organize, and store data in your Django database.
- **Dynamic analysis**: Compute common summaries (e.g., totals, means, frequencies).
- **Visual outputs**: Generate charts (bar, line, pie, scatter) for insightful reporting.
- **Export options**: Download analyzed data or charts for sharing.

---

## 🚧 Getting Started

### Requirements

- Python 3.10+
- Django 4.x
- `pandas`, `openpyxl`, `matplotlib` (or `plotly`), and other dependencies listed in `requirements.txt`

### Installation

```bash
git clone https://github.com/Sachin-005/Graphixcel-Excel-Data-Analysis-Application.git
cd Graphixcel-Excel-Data-Analysis-Application
python -m venv venv
source venv/bin/activate    # or `venv\Scripts\activate` on Windows
pip install -r requirements.txt
>>>>>>> b1a17c62beb5745e69cca99b42892cb57fac2923
