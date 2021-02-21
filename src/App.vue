<!--Mi proyecto 2021-->

<template>
    <div class="h-screen flex flex-row justify-center items-center space-x-8 text-center">
            <Target v-for="(l,k) of list" :key="k" :value="l" />
    </div>
</template>

<script>
import Target from "./components/Target";
export default {
    components: {Target},
    data(){
        return{
            list:[
                {
                    color: "bg-gradient-to-r from-yellow-400 via-red-500 to-pink-500",
                    texthover: "hover:text-white",
                    image: "https://www.logo.wine/a/logo/Instagram/Instagram-Glyph-Black-Logo.wine.svg",
                    name: "INSTAGRAM",
                    description: "Instagram is an American, free, online photo-sharing app and social network owned by Facebook Inc. It was founded in San Francisco by Kevin Systrom and Mike Krieger and launched in October 2010 on iOS.",
                    link: "https://www.instagram.com/?hl=es-la",
                    boton: "Ir a Instagram"
                },
                {
                    image: "https://www.logo.wine/a/logo/Gmail/Gmail-Logo.wine.svg",
                    name: "GMAIL",
                    description: "The content of this site is provided on an “as-is” and “as available” basis, and it is intended for non-commercial, informational purposes only, to educate and inform its website visitors about the Gmail log",
                    link: "https://accounts.google.com/signin/v2/identifier?service=mail&passive=true&rm=false&continue=https%3A%2F%2Fmail.google.com%2Fmail%2F&ss=1&scc=1&ltmpl=default&ltmplcache=2&emr=1&osid=1&flowName=GlifWebSignIn&flowEntry=ServiceLogin",
                    boton: "Ir a Gmail"
                },
                {
                    image: "https://www.logo.wine/a/logo/Discord_(software)/Discord_(software)-Logo-Color-Logo.wine.svg",
                    name: "DISCORD",
                    description: "The content of this site is provided on an “as-is” and “as available” basis, and it is intended for non-commercial, informational purposes only, to educate and inform its website visitors about the Discord logo.",
                    link: "https://discord.com/",
                    boton: "Ir a Discord"
                },
                {
                    image: "https://www.logo.wine/a/logo/Snapchat/Snapchat-Ghost-Outlined-Logo.wine.svg",
                    name: "SNAPCHAT",
                    description: "The content of this site is provided on an “as-is” and “as available” basis, and it is intended for non-commercial, informational purposes only, to educate and inform its website visitors about the Discord logo.",
                    link: "https://www.snapchat.com/l/es/",
                    boton: "Ir a Snapchat"
                },
                {
                    color: "bg-gradient-to-r from-green-400 via-blue-600 to-blue-500",
                    image: "https://www.logo.wine/a/logo/Skype_for_Business_Server/Skype_for_Business_Server-Logo.wine.svg",
                    name: "SKYPE",
                    description: "The content of this site is provided on an “as-is” and “as available” basis, and it is intended for non-commercial, informational purposes only, to educate and inform its website visitors about the Skype logo.",
                    link: "https://www.skype.com/es/",
                    boton: "Ir a Skype"
                }
            ]
        };
    }
}
</script>