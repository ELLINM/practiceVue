<template>
    <div>
        <table>
            <tr>
                <th>Name</th>
                <th>NickName</th>
                <th>Image</th>
                <th>Position</th>
                <th>Debut</th>
            </tr>
            <tr v-for="item in items" :key="item.name">
                <td><span v-html="item.name"></span></td>
                <td><span v-html="item.nickName"></span></td>
                <td><img class="image" v-bind:src="item.image"></td>
                <td><span v-html="item.position"></span></td>
                <td><span v-html="item.debut"></span></td>
            </tr>
        </table>
    </div>
</template>

<script>
    export default {
        data() {
            return {
                items: [
            {
                "name": "<strong>최우제</strong>",
                "nickName": "Zeus",
                "image": "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTsnP3VZy8eBdC1MJUMPIycS_O63Sidjwa0iuqEtUIKqsjmI8mLgM23mJ2BEm3Ya8XJoB4&usqp=CAU",
                "position": "Top",
                "debut": "2021.02.03"
            },
            {
                "name": "<strong>문현준</strong>",
                "nickName": "Oner",
                "image": "https://editors.dexerto.com/wp-content/uploads/2022/06/16/T1-Oner.jpg",
                "position": "Jungle",
                "debut": "2021.02.21"
            },
            {
                "name": "<strong>이상혁</strong>",
                "nickName": "Faker",
                "image": "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRwFbk03z-aGv1LY11Wa6gAHx0wJEae7B7lAA&usqp=CAU",
                "position": "Mid",
                "debut": "2013.02.13"
            },
            {
                "name": "<strong>이민형</strong>",
                "nickName": "Gumayusi",
                "image": "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSiU82WI6CeD6k8hwLAbMvH_WjjPRs77YniEw&usqp=CAU",
                "position": "AD",
                "debut": "2020.09.08"
            },
            {
                "name": "<strong>류민석</strong>",
                "nickName": "Keria",
                "image": "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR7Kwk2FBN7rb_kfjR-cyytQPBLH_Ves-b0bw&usqp=CAU",
                "position": "SUP",
                "debut": "2019.12.06"
            }
            ]
        }
    }
}
</script>

<style>
.image {
    width:380px;
    height:220px;
    overflow:hidden;
    margin:0 auto;
}
</style>