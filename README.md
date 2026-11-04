# CPSY 300 - Group 11: Recipe Insights

Team: Adel Tammam (host), Romhel Veroy (repository), Jonah Gile (pipeline)

Live app: https://ca-recipes-group11.icysea-aea67fe8.canadacentral.azurecontainerapps.io

## Run locally

    cd cpsy300group11
    npm install
    npm run dev

Then open http://localhost:3000

## Deploy

Every merge to main runs .github/workflows/deploy.yml: it builds the image, tags it with the commit ID, pushes it to Azure Container Registry and updates the container app.
