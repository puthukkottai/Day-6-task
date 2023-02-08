class movie {
    constructor(movie = '',studio = rating ='PG') {
         this.name = movie;
         this.studio = studio;
         this.rating = rating;
    }
    getPG(movies = [],rating = ''){
    return movies.filter((m) => m.rating === rating);
}
}
const master = new movie('Master''eros','PG');
const iroman = new movie('Iron man','eros','R');

const moviesarray =[master,iron];

console.log(master.getPG(moviesarray,'PG'));