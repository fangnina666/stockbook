
# 股票報告

<div id="file-list"></div>

<script>
  const owner = 'fangnina666';
  const repo = 'stockbook';
  const folder = 'reports_his';
  
  fetch(`https://api.github.com/repos/${owner}/${repo}/contents/${folder}`)
    .then(response => response.json())
    .then(files => {
      let html = '<ul>';
      files.forEach(file => {
        if (file.name.endsWith('.md')) {
          html += `<li><a href="${file.name}">${file.name}</a></li>`;
        }
      });
      html += '</ul>';
      document.getElementById('file-list').innerHTML = html;
    });
</script>
