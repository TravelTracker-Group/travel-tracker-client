# Contributor Doc

## The First Step

If you want to participate in the Travel Tracker project, please first fork this repository and set it up as follows:

```bash
git clone https://github.com/your-username/travel-tracker-client.git
cd ./travel-tracker-client
git remote add upstream git@github.com:TravelTracker-Group/travel-tracker-client.git
git remote set-url --push upstream no-pushing
```

Then run `git remote -v` and you should see the following results:

```text
origin	https://github.com/your-username/travel-tracker-client.git (fetch)
origin	https://github.com/your-username/travel-tracker-client.git (push)
upstream	git@github.com:TravelTracker-Group/travel-tracker-client.git (fetch)
upstream	no-pushing (push)
```

**Note**: Replace `your-username` with your actual username.