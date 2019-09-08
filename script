var allDownloadLinks = document.links;

var downloaded = 0;
var downloadedArr = [];

for (var i = 0; i < allDownloadLinks.length; i++) {
	if (allDownloadLinks[i].getAttribute("href").startsWith("https://unsplash.com/photos/") && allDownloadLinks[i].getAttribute("href").endsWith("/download?force=true")) {
		if (!downloadedArr.includes(allDownloadLinks[i].getAttribute("href"))) {
			window.open(allDownloadLinks[i].getAttribute("href"));
			
			downloaded++;
			downloadedArr.push("allDownloadLinks[i].getAttribute('href')");
		}
	}
}

console.log("Successfully downloaded " + downloaded + " Unsplash images.");
