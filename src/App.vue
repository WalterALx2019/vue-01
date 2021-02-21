<!--Mi proyecto 2021-->
<template>   
    <div class="flex flex-row justify-center items-center text-center bg-white dark:bg-gray-900">
       <div class="grid lg:grid-cols-3 gap-8 pt-20 pb-20 md:grid-cols-2">
            <Target v-for="(l,k) of list" :key="k" :value="l" />
       </div>
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
                    name: "instagram",
                    description: "Instagram is an American, free, online photo-sharing app and social network owned by Facebook Inc. It was founded in San Francisco by Kevin Systrom and Mike Krieger and launched in October 2010 on iOS.",
                    link: "https://www.instagram.com/?hl=es-la",
                    boton: "Ir a Instagram"
                },
                {
                    color: "bg-red-300",
                    texthover: "hover:text-white",
                    image: "https://www.logo.wine/a/logo/Gmail/Gmail-Logo.wine.svg",
                    name: "gmail",
                    description: "The content of this site is provided on an “as-is” and “as available” basis, and it is intended for non-commercial, informational purposes only, to educate and inform its website visitors about the Gmail log",
                    link: "https://accounts.google.com/signin/v2/identifier?service=mail&passive=true&rm=false&continue=https%3A%2F%2Fmail.google.com%2Fmail%2F&ss=1&scc=1&ltmpl=default&ltmplcache=2&emr=1&osid=1&flowName=GlifWebSignIn&flowEntry=ServiceLogin",
                    boton: "Ir a Gmail"
                },
                {
                    color: "bg-gradient-to-r from-gray-400 via-gray-400 to-gray-600",
                    texthover: "hover:text-white",
                    image: "https://www.logo.wine/a/logo/Discord_(software)/Discord_(software)-Logo-Black-Logo.wine.svg",
                    name: "discord",
                    description: "The content of this site is provided on an “as-is” and “as available” basis, and it is intended for non-commercial, informational purposes only, to educate and inform its website visitors about the Discord logo.",
                    link: "https://discord.com/",
                    boton: "Ir a Discord"
                },
                {
                    color: "bg-gradient-to-r from-yellow-400 via-yellow-400 to-yellow-600",
                    texthover: "hover:text-white",
                    image: "https://www.logo.wine/a/logo/Snapchat/Snapchat-Ghost-Outlined-Logo.wine.svg",
                    name: "snapchat",
                    description: "Snapchat is a popular messaging app that lets users exchange pictures and videos (called snaps) that are meant to disappear after they're viewed. It's advertised as a new type of camera.the essential function.",
                    link: "https://www.snapchat.com/l/es/",
                    boton: "Ir a Snapchat"
                },
                {
                    color: "bg-blue-200",
                    texthover: "hover:text-white",
                    image: "https://www.logo.wine/a/logo/Skype_for_Business_Server/Skype_for_Business_Server-Logo.wine.svg",
                    name: "skype",
                    description: "The content of this site is provided on an “as-is” and “as available” basis, and it is intended for non-commercial, informational purposes only, to educate and inform its website visitors about the Skype logo.",
                    link: "https://www.skype.com/es/",
                    boton: "Ir a Skype"
                },
                {
                    color: "bg-gradient-to-r from-green-400 via-green-400 to-green-600",
                    texthover: "hover:text-white",
                    image: "https://www.logo.wine/a/logo/Spotify/Spotify-Icon-Black-Logo.wine.svg",
                    name: "spotify",
                    description: "Spotify is a digital music, podcast, and video streaming service that gives you access to millions of songs and other content from artists all over the world. Basic functions such as playing music are totally free.",
                    link: "https://www.spotify.com/es/",
                    boton: "Ir a Spotify"
                },
            ]
        };
    }
}
</script>