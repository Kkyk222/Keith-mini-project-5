<script>
    import Header from '$lib/Header.svelte';
    import Section from '$lib/Section.svelte';
    import Footer from '$lib/Footer.svelte';
     
let myInfo = {
    title: "Info",
    item1: "Keith Khor Yi Khang",
    item2: 15,
    item3: "SMJK Chung Ling",
}
let Hobby = {
    title: "Hobby",
    item1: "Gaming",
    item2: "Play badminton",
    item3: "Sleeping",
}
let Personality = {
    title: "Personality",
    item1: "Kind",
    item2: "Quiet",
    item3: "Humble",
}


</script>
<Header title = "My Biography"/>

<Section {...myInfo} />
<Section {...Hobby} />
<Section {...Personality} />
<Footer gitHub="https://github.com/Kkyk222/Keith-mini-project-5"/>


