const cloudName = "db5wqzdth"; // 너의 cloud name
const apiUrl = `https://res.cloudinary.com/${cloudName}/image/list`;

async function loadRandomImage() {
  const folder = document.getElementById("folderSelect").value;
  try {
    const response = await fetch(`${apiUrl}/${folder}.json`);
    const data = await response.json();
    const images = data.resources;

    if (!images || images.length === 0) {
      alert("No images found in this folder.");
      return;
    }

    const randomIndex = Math.floor(Math.random() * images.length);
    const imageUrl = `https://res.cloudinary.com/${cloudName}/image/upload/${images[randomIndex].public_id}.jpg`;

    document.getElementById("imageContainer").innerHTML = `
      <img src="${imageUrl}" alt="Random Image" />
    `;
  } catch (err) {
    console.error(err);
    alert("Could not load images. Make sure the folder is public.");
  }
}
