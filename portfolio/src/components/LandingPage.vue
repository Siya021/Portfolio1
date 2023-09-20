<template>
    <div class="container-fluid">
        <div class="row">
            <div class="col-md-8">
                <h2 style="font-size: 80px; font-weight: 700;">I'm</h2>
                <h1>Siyamthanda Mazokwana</h1>
                <h2 class="role">A Frontend Developer</h2>
                <div class="container">
                    <ul>
                        <li>
                            <a href=""><svg xmlns="http://www.w3.org/2000/svg" width="36" height="36" fill="currentColor"
                                    class="bi bi-folder-symlink" viewBox="0 0 16 16">
                                    <path
                                        d="m11.798 8.271-3.182 1.97c-.27.166-.616-.036-.616-.372V9.1s-2.571-.3-4 2.4c.571-4.8 3.143-4.8 4-4.8v-.769c0-.336.346-.538.616-.371l3.182 1.969c.27.166.27.576 0 .742z" />
                                    <path
                                        d="m.5 3 .04.87a1.99 1.99 0 0 0-.342 1.311l.637 7A2 2 0 0 0 2.826 14h10.348a2 2 0 0 0 1.991-1.819l.637-7A2 2 0 0 0 13.81 3H9.828a2 2 0 0 1-1.414-.586l-.828-.828A2 2 0 0 0 6.172 1H2.5a2 2 0 0 0-2 2zm.694 2.09A1 1 0 0 1 2.19 4h11.62a1 1 0 0 1 .996 1.09l-.636 7a1 1 0 0 1-.996.91H2.826a1 1 0 0 1-.995-.91l-.637-7zM6.172 2a1 1 0 0 1 .707.293L7.586 3H2.19c-.24 0-.47.042-.683.12L1.5 2.98a1 1 0 0 1 1-.98h3.672z" />
                                </svg><label for="explore"><small>Explore</small></label></a>
                        </li>
                        <li>

                            <a href=""> <svg xmlns="http://www.w3.org/2000/svg" width="36" height="36" fill="currentColor"
                                    class="bi bi-file-earmark-pdf" viewBox="0 0 16 16">
                                    <path
                                        d="M14 14V4.5L9.5 0H4a2 2 0 0 0-2 2v12a2 2 0 0 0 2 2h8a2 2 0 0 0 2-2zM9.5 3A1.5 1.5 0 0 0 11 4.5h2V14a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V2a1 1 0 0 1 1-1h5.5v2z" />
                                    <path
                                        d="M4.603 14.087a.81.81 0 0 1-.438-.42c-.195-.388-.13-.776.08-1.102.198-.307.526-.568.897-.787a7.68 7.68 0 0 1 1.482-.645 19.697 19.697 0 0 0 1.062-2.227 7.269 7.269 0 0 1-.43-1.295c-.086-.4-.119-.796-.046-1.136.075-.354.274-.672.65-.823.192-.077.4-.12.602-.077a.7.7 0 0 1 .477.365c.088.164.12.356.127.538.007.188-.012.396-.047.614-.084.51-.27 1.134-.52 1.794a10.954 10.954 0 0 0 .98 1.686 5.753 5.753 0 0 1 1.334.05c.364.066.734.195.96.465.12.144.193.32.2.518.007.192-.047.382-.138.563a1.04 1.04 0 0 1-.354.416.856.856 0 0 1-.51.138c-.331-.014-.654-.196-.933-.417a5.712 5.712 0 0 1-.911-.95 11.651 11.651 0 0 0-1.997.406 11.307 11.307 0 0 1-1.02 1.51c-.292.35-.609.656-.927.787a.793.793 0 0 1-.58.029zm1.379-1.901c-.166.076-.32.156-.459.238-.328.194-.541.383-.647.547-.094.145-.096.25-.04.361.01.022.02.036.026.044a.266.266 0 0 0 .035-.012c.137-.056.355-.235.635-.572a8.18 8.18 0 0 0 .45-.606zm1.64-1.33a12.71 12.71 0 0 1 1.01-.193 11.744 11.744 0 0 1-.51-.858 20.801 20.801 0 0 1-.5 1.05zm2.446.45c.15.163.296.3.435.41.24.19.407.253.498.256a.107.107 0 0 0 .07-.015.307.307 0 0 0 .094-.125.436.436 0 0 0 .059-.2.095.095 0 0 0-.026-.063c-.052-.062-.2-.152-.518-.209a3.876 3.876 0 0 0-.612-.053zM8.078 7.8a6.7 6.7 0 0 0 .2-.828c.031-.188.043-.343.038-.465a.613.613 0 0 0-.032-.198.517.517 0 0 0-.145.04c-.087.035-.158.106-.196.283-.04.192-.03.469.046.822.024.111.054.227.09.346z" />
                                </svg><label for="Download"><small>DownloadCV</small></label></a>
                        </li>
                    </ul>

                </div>
            </div>
            <div class="col-md-4">

            </div>
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.role {
    color: rgba(86, 32, 43, 255);
}

.col-md-8 ul {
    display: flex;
    justify-content: flex-start;
    text-decoration: none;
    list-style: none;
    margin: 50px;
    border-top: #672c33 solid 3px;
    padding-top: 20px;
}
.container{
    margin-left:250px ;
}

.col-md-4 {
    padding: 15%;
    background-color: #672c33;
}

.container-fluid {
    margin-top: 100px;
    border: 4px solid black;
    color: black;
    text-align: start;

}

a {
    color: black;
    padding: 10px;
}
a :hover{
    color: #672c33;
    transition: background-color 0.5s ease;;
}

h1 {
    font-size: 83px;
    font-weight: 800;
}

h2 {
    font-size: 60px;
    font-weight: 800;
}
</style>