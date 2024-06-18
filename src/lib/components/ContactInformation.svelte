<script>
    import SocialIcons from '@rodneylab/svelte-social-icons';
    const linkedinUrl = 'https://www.linkedin.com/in/ilanlifshitz';
    const githubUrl = 'https://github.com/ilanlee';
    const whatsappUrl = 'https://wa.me/+14345173443';
  </script>
  
  <div class="container mx-auto px-4 py-8 flex justify-center space-x-6">
    <a href={linkedinUrl} target="_blank" rel="noopener noreferrer">
      <span class="h-10 w-10">
        <SocialIcons network="linkedin" alt=""/>
      </span> 
    </a>
  
    <a href={githubUrl} target="_blank" rel="noopener noreferrer">
      <span class="h-10 w-10">
        <SocialIcons network="github" alt=""/>
      </span>
    </a>
  
    <a href={whatsappUrl} target="_blank" rel="noopener noreferrer">
      <span class="h-10 w-10">
        <SocialIcons network="whatsapp" alt=""/>
      </span> 
    </a>
  </div>