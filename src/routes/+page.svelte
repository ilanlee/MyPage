<script>
	import AboutMe from "../lib/components/AboutMe.svelte";
	import ContactInformation from "../lib/components/ContactInformation.svelte";
	import ContactQrCode from "../lib/components/ContactQrCode.svelte";
	import WorkingExperience from "../lib/components/WorkingExperience.svelte";

</script>

<div class="container mx-auto px-4 py-8 grid grid-cols-2 gap-8"> 
  <AboutMe />
  <ContactQrCode /> 
</div>

<ContactInformation/>
<WorkingExperience/>