<body> 
	   <iframe
      width="560"
      height="315"
      src="https://www.youtube.com/embed/uSz2_HCbfBs"
      frameborder="0"
      allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture"
      allowfullscreen
    ></iframe>

    <div id="chat-embed-wrapper" class="chat"></div>

    <script>
      let frame = document.createElement('iframe');
      frame.referrerPolicy = 'origin';
      frame.src = 'https://www.youtube.com/live_chat?v=uSz2_HCbfBs&embed_domain=' + window.location.hostname;
      frame.frameBorder = '0';
      frame.id = 'chat-embed';
      let wrapper = document.getElementById('chat-embed-wrapper');
      wrapper.appendChild(frame);
    </script>
</body> 
