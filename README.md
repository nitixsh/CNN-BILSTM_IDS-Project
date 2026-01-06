git clone https://github.com/<username>/CNN-BILSTM_IDS-Project.git
cd CNN-BILSTM_IDS-Project
mkdir models data src notebooks
echo "Models" > models/README.md
echo "Data" > data/README.md
echo "Scripts" > src/README.md
echo "Notebooks" > notebooks/README.md
git add .
git commit -m "Created folder structure"
git push origin main
